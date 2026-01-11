<div>
  <h1>GymZone - Fitness Website</h1>

  <p>
    <strong>About Project:</strong> 
    A responsive fitness gym website showcasing classes, programs, and trainer information through smooth animations and mobile-friendly navigation. Built with semantic HTML5, CSS custom properties for consistent theming, and vanilla JavaScript for interactive features all organized in clean, well-structured code that gyms and fitness centers can easily customize.
  </p>

  <p> 
    <strong>What I learned:</strong>
    CSS Grid and Flexbox for responsive layouts, implemented scroll-triggered header effects, created mobile hamburger menu with overlay, and built horizontal scrollable sections with custom scrollbar styling.
  </p>

  <p> 
    <strong>Personal Note:</strong>
    I started building HTML, CSS, and JavaScript projects in 2022. <br />
    At that time, I focused on learning first and began uploading to GitHub recently. <br />
    Now I'm working with <strong>React.js</strong> and <strong>Next.js</strong>, and seeking opportunities as a <strong>frontend</strong> or <strong>web developer</strong>.
  </p>
</div>

<details open> 
  <summary><h2>Project More Details</h2></summary>

  <details> 
    <summary><h4>What's Inside</h4></summary>
    <ul>
      <li><strong>Hero Section</strong> - Full-width banner with animated circles, motivational headline, and call-to-action button</li>
      <li><strong>About Section</strong> - Gym introduction with animated fitness text, coach profile, and dual-column layout</li>
      <li><strong>Video Section</strong> - Interactive video card with play button and pulsing animation effect</li>
      <li><strong>Classes Section</strong> - Horizontal scrollable fitness class cards with progress bars and hover effects</li>
      <li><strong>Blog Section</strong> - Latest news articles with dates, images, and read more links</li>
      <li><strong>Footer</strong> - Operating hours, contact information, newsletter signup, and social media links</li>
      <li><strong>Mobile Navigation</strong> - Full-screen overlay menu with smooth slide animation</li>
      <li><strong>Sticky Header</strong> - Fixed navigation that appears after scrolling with background transition</li>
      <li><strong>Back to Top</strong> - Floating button for quick page navigation</li>
    </ul>
  </details>

  <details> 
    <summary><h4>Technologies Used</h4></summary>
    <ul>
      <li><strong>HTML5</strong> - Semantic markup with proper ARIA labels for accessibility</li>
      <li><strong>CSS3</strong> - Modern styling with Grid, Flexbox, custom properties, keyframe animations, and transforms</li>
      <li><strong>JavaScript (ES6)</strong> - Vanilla JS for navigation toggle, scroll effects, and interactive elements</li>
      <li><strong>Google Fonts</strong> - Catamaran and Rubik font families for professional typography</li>
      <li><strong>Ionicons</strong> - SVG icons for UI elements and social media</li>
      <li><strong>CSS Custom Properties</strong> - Variables for colors, typography, and spacing for easy customization</li>
      <li><strong>CSS Animations</strong> - Rotating circles, moving elements, pulsing buttons, and smooth transitions</li>
      <li><strong>Media Queries</strong> - Responsive breakpoints at 575px, 768px, 992px, and 1200px</li>
    </ul>
  </details>

  <details> 
    <summary><h4>Project Structure</h4></summary>
    <pre>
    gym-zone/
    │
    ├── index.html                 # Main HTML structure with all sections
    │
    ├── assets/
    │   ├── css/
    │   │   └── style.css         # Complete styles, animations, and responsive design
    │   │
    │   ├── js/
    │   │   └── script.js         # Navigation toggle, header scroll, back-to-top functionality
    │   │
    │   └── images/               # Hero banners, class images, blog photos, icons
    │
    └── README.md                 # Project documentation
    </pre>
  </details>

  <details> 
    <summary><h4>Key Features</h4></summary>
    <ul>
      <li><strong>Fully Responsive Design</strong> - Works seamlessly on all devices from 320px mobile to 1920px+ desktop</li>
      <li><strong>Animated Hero Banner</strong> - Rotating circle graphics and floating elements with smooth movement</li>
      <li><strong>Mobile-First Navigation</strong> - Full-screen overlay menu with close button and smooth transitions</li>
      <li><strong>Horizontal Scrollable Cards</strong> - Classes and blog sections with custom scrollbar styling</li>
      <li><strong>Progress Indicators</strong> - Visual class capacity bars with percentage display</li>
      <li><strong>Interactive Video Card</strong> - Play button with animated pulse effect</li>
      <li><strong>Scroll-Triggered Header</strong> - Transparent header becomes solid with shadow after 100px scroll</li>
      <li><strong>Hover Effects</strong> - Image zoom on cards, color transitions on buttons and links</li>
      <li><strong>Newsletter Subscription</strong> - Email input form in footer with submit button</li>
      <li><strong>Back to Top Button</strong> - Floating button appears when scrolling down</li>
      <li><strong>Cross-Browser Compatible</strong> - Tested on Chrome, Firefox, Safari, Edge, and Opera</li>
      <li><strong>Easy Customization</strong> - CSS variables allow quick color and font changes</li>
    </ul>
  </details>

  <details> 
    <summary><h4>Quick Start</h4></summary>
    <ol>
      <li>
        <strong>Clone the repository:</strong>
        <pre><code>git clone https://github.com/nawazdevx/gym-zone.git</code></pre>
      </li>

      <li>
        <strong>Open the project:</strong>
        <ul>
          <li>Open <code>index.html</code> directly in your browser</li>
          <li>Or run a local server:</li>
        </ul>

        <pre><code>python -m http.server 3000</code></pre>
        Then visit <code>http://localhost:3000</code>
      </li>

      <li>
        <strong>Start Customizing:</strong>
        <ul>
          <li>Update gym name and content in <code>index.html</code></li>
          <li>Change colors in <code>style.css</code> using CSS variables</li>
          <li>Replace images in <code>assets/images/</code> folder</li>
          <li>Update contact details in footer section</li>
        </ul>
      </li>
    </ol>
  </details>

  <details> 
    <summary><h4>Customization</h4></summary>
    <ul>
      <li><strong>Text Content:</strong> Edit directly in <code>index.html</code> - update gym name, class descriptions, blog posts, and contact information</li>
      <li><strong>Colors:</strong> Update CSS variables in <code>:root</code> selector at the top of <code>style.css</code>
        <pre><code>:root {
  --coquelicot: hsl(12, 98%, 52%);                 /* Primary red-orange color */
  --rich-black-fogra-29-1: hsl(210, 26%, 11%);     /* Dark backgrounds */
  --white: hsl(0, 0%, 100%);                       /* White text/backgrounds */
}</code></pre>
      </li>
      <li><strong>Images:</strong> Replace files inside <code>assets/images/</code> with your own gym photos (keep same filenames or update HTML references)</li>
      <li><strong>Fonts:</strong> Change the Google Fonts link in HTML <code>&lt;head&gt;</code> section and update <code>--ff-catamaran</code> and <code>--ff-rubik</code> variables</li>
      <li><strong>Classes Section:</strong> Add or remove class cards by duplicating <code>&lt;li class="scrollbar-item"&gt;</code> elements</li>
      <li><strong>Blog Posts:</strong> Update blog cards with new images, dates, titles, and descriptions</li>
      <li><strong>Footer Content:</strong> Modify operating hours, contact details, and social media links</li>
      <li><strong>Animations:</strong> Adjust animation timing in <code>@keyframes</code> sections and transition properties</li>
    </ul>
  </details>

</details>

<p> 
  <strong>License:</strong>
  This project is licensed under the <a href="https://choosealicense.com/licenses/mit/">MIT License</a>.
</p>

<p> 
  <strong>Contact:</strong> 
  Connect with me on <a href="https://www.linkedin.com/in/nawazdevx">LinkedIn</a> or visit my <a href="https://nawazdevx.vercel.app/">Portfolio</a>.
</p>

<p> 
  <strong>Support:</strong> 
  Found this helpful? Give it a ⭐ on GitHub! Thank you.
</p>

<br />

<div>
  <h2>Project Preview</h2>

  <p>
    <strong>You can view the live project here ➜</strong>
    <a href="https://nawazdevx.github.io/gym-zone/" target="_blank">
      <strong>Live Demo</strong>
    </a>
  </p>

  <img src="./assets/images/readme-image.png" alt="Desktop Demo" />
</div>

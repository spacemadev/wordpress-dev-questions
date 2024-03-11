## Basic WordPress Knowledge:

**1. What's the fundamental distinction between WordPress.com and WordPress.org?**

**Answer:** 
WordPress.com is a hosted platform where you don't have full control over the site's code or functionality. It's suitable for beginners. WordPress.org is self-hosted software, offering complete customization and control; however, you're responsible for hosting and maintenance.

**2. Explain the core components of a WordPress website: themes, plugins, and core files.**

**Answer:**
- **Themes:** Control the website's appearance, including layout, colors, and typography. You can use pre-built themes or develop custom ones.
- **Plugins:** Extend WordPress functionality by adding features like contact forms, security enhancements, e-commerce capabilities, etc.
- **Core Files:** The foundation of WordPress, containing essential code for managing content, users, settings, and security. Updates are crucial for stability and security.

## Technical Skills:

**1. Describe the process of creating a custom WordPress theme from scratch.**

**Answer:**
1. **Planning and Design:** Sketch wireframes, define user flows, and choose color schemes and typography.
2. **Theme Folder Structure:** Create the appropriate folder hierarchy (styles, scripts, templates, etc.)
3. **Theme Files:** Develop core theme files like `style.css` (theme information), `header.php` (site header), `footer.php` (site footer), and template files (`page.php`, `single.php`, etc.) for specific content types.
4. **Enqueue Styles and Scripts:** Use `wp_enqueue_style` and `wp_enqueue_script` functions to include theme-specific CSS and JavaScript.
5. **Template Hierarchy:** Leverage WordPress's template hierarchy to control how different content types are displayed.
6. **Theme Customization:** Implement theme options for users to personalize colors, fonts, and layouts.
7. **Testing and Validation:** Thoroughly test the theme's functionality and responsiveness across different browsers and devices.

## Troubleshooting:

**1. Explain how you would troubleshoot a conflict between plugins on a WordPress site.**

**Answer:**
1. **Deactivate All Plugins:** Start by deactivating all plugins and testing if the issue persists.
2. **Reactivate One by One:** Systematically reactivate plugins one at a time, testing after each reactivation to pinpoint the problematic plugin.
3. **Check Plugin Documentation:** Refer to the documentation of the identified plugin for troubleshooting steps or known conflicts.
4. **Search Forums:** Search online forums and communities for solutions related to the specific plugins involved.
5. **Contact Plugin Developer:** If the above steps don't resolve the issue, contact the plugin developer for further assistance.

## WordPress Hooks and Actions:

**1. What are WordPress hooks and actions, and how would you use them to customize functionality?**

**Answer:**
- **Hooks:** Integration points within WordPress's core execution flow that allow you to inject your custom code at specific points.
- **Actions:** Triggered at designated points, allowing you to modify data or execute tasks after the event occurs (e.g., `after_setup_theme`, `wp_enqueue_scripts`).
- **Filters:** Allow you to intercept data before it's used by WordPress and modify it (e.g., `the_title`, `the_content`).
- **Usage:** Use hooks (actions and filters) to extend WordPress behavior without modifying core files, making upgrades easier.

## Security and Performance:

**1. Describe your approach to securing a WordPress website.**

**Answer:**
1. **Strong Passwords:** Enforce strong passwords for all users and administrators. Use a password manager.
2. **Regular Updates:** Keep WordPress core, themes, and plugins updated to address security vulnerabilities.
3. **Security Plugins:** Consider using a well-regarded security plugin that provides features like login attempts monitoring, malware scanning, and firewalls.
4. **Limited User Roles:** Assign user roles with the bare minimum permissions required for their tasks.
5. **Backups:** Regularly back up your website database and files.
6. **Secure Hosting:** Choose a reputable hosting provider with security measures like intrusion detection and prevention systems.


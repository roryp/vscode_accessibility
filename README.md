# VS Code Accessibility Demo

## Demo 1 - WCAG
1. **WCAG accessibility standards:**
    - Learn about WCAG accessibility standards and their importance in creating inclusive software [here](https://aka.ms/accessibilityprinciples).
    - Test [Accessible University Demo Site - Inaccessible Version](https://www.washington.edu/accesscomputing/AU/inaccessible.html) with Accessibility Insights:
        1. Open the site in your browser.
        2. Run Accessibility Insights by clicking on the extension and selecting "Fast Pass".
        3. Observe and note down identified issues.
    - Accessibility categories:
        - **Perceivable (Visible):** Insufficient color contrast, no alternate text on images, inaccessible visual content in video.
        - **Operable (Navigable):** No "skip to main content" link, inaccessible keyboard interface, no visible indication of focus.
        - **Understandable:** Language not specified, form not properly labelled, inaccessible CAPTCHA.
        - **Robust:** Missing landmark regions, inaccessible input validation, confusion between links and buttons.

## Demo 2 - BUILT IN VScode Accessibility features
- **Perceivable (Visible):** Accessibility documentation, Alt+F1 for "Show Accessibility Help", adjustable font size, variety of color themes like Pitaya Smoothie.
- **Operable (Navigable):** Full keyboard navigation support, tab trapping, accessible integrated terminal.
- **Understandable:** Zen Mode for distraction-free coding, accessible settings editor with full keyboard navigation.
- **Robust:** Compatibility with various screen readers, "Editor: Accessibility Support" setting for future tech, Accessibility Inspection Tools for UI.

## Demo 3 - Coding demo

1. **Axe Linter extension in VS Code:**
    - Install the Axe linter extension in Visual Studio Code.
    - Demonstrate how it catches accessibility issues during coding.
2. **Demo Good and Bad HTML Files:**
    - Using the two HTML files, one with good accessibility practices and another with bad ones.
    - Show the differences and the issues caught by the Axe linter extension.
3. **Scan Good and Bad HTML files with Accessibility Insights:**
    - Open both files in your browser.
    - Run Accessibility Insights on both files to compare issues.
4. **Automate Accessibility Testing with Playwright and Axe Core:**
    - Run the test.js file to run accessibility tests using Axe Core.
        npm install
        node test.js
    - Log the results in the console.

## Demo 4 – Using AI to help test (Bing, Copilot and A11ybot)
Learn more about using AI to assist in testing [here](https://github.com/sinedied/a11y-ai).

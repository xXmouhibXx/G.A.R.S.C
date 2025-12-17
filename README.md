# G.A.R.S.C - Animal Association Website

## Table of Contents

-   [About the Project](#about-the-project)
-   [Technologies Used](#technologies-used)
-   [Project Structure](#project-structure)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Testing](#testing)
-   [Contributing](#contributing)
-   [License](#license)
-   [Contact](#contact)

## About the Project

`G.A.R.S.C` is a static web project designed to serve as an informational and interactive platform for an animal association. Built with fundamental web technologies, it aims to provide visitors with comprehensive details about the association's mission, history, team, and strategic plans, while also offering interactive elements such as a questionnaire and forms for community engagement.

The project features multiple dedicated pages:
-   **Homepage (`index.html`):** The main entry point, likely providing an overview.
-   **Articles (`Article.html`):** For sharing news, stories, or educational content.
-   **Questionnaire (`Questionnaire.html`):** To gather feedback or engage users.
-   **Information Table (`Table.html`):** Possibly for displaying data, events, or statistics.
-   **Discovery (`decouverte.html`):** To introduce new users to the association.
-   **Team (`equipe.html`):** Profiles of the association members.
-   **Association Form (`form-association.html`):** For potential members or partners to join.
-   **History (`historique.html`):** A timeline or narrative of the association's past.
-   **Strategic Plan (`plan-strategique.html`):** Outlining future goals and initiatives.

## Technologies Used

This project is built using standard web technologies for front-end development:

*   **HTML5:** For structuring the content of the web pages.
*   **CSS3:** For styling the visual presentation and layout of the website.
*   **JavaScript:** For adding interactivity and dynamic behaviors.
*   **Modernizr:** A JavaScript library for detecting HTML5 and CSS3 features in the user's browser, enabling progressive enhancements.

## Project Structure

The repository is organized into a clear and logical structure:


G.A.R.S.C/
├── HTML/                      # Contains all primary HTML content pages
│   ├── Article.html
│   ├── Questionnaire.html
│   ├── Table.html
│   ├── decouverte.html        # Discovery page
│   ├── equipe.html            # Team page
│   ├── form-association.html  # Association registration/contact form
│   ├── historique.html        # History page
│   └── plan-strategique.html  # Strategic plan page
├── css/                       # Contains all CSS stylesheets
│   ├── Questions.css
│   ├── Table.css
│   ├── article.css
│   ├── exemple.css
│   ├── form.css
│   ├── main.css
│   ├── navbar.css             # Styles for navigation bars
│   ├── navbar1.css            # Additional navbar styles
│   └── styles.css             # General styles
├── js/                        # Contains all JavaScript files
│   ├── exemple.js
│   ├── main.js
│   ├── plugins.js
│   └── vendor/                # Third-party vendor scripts
│       └── modernizr-3.11.2.min.js # Modernizr library
└── index.html                 # The main homepage of the website


## Installation

This is a static website, so no complex installation or server-side setup is required.

To get a local copy up and running, follow these simple steps:

1.  **Clone the repository:**
    bash
    git clone https://github.com/xXmouhibXx/G.A.R.S.C.git
    
2.  **Navigate to the project directory:**
    bash
    cd G.A.R.S.C
    
3.  **Open the website:**
    Simply open the `index.html` file in your preferred web browser.
    (e.g., `file:///path/to/your/G.A.R.S.C/index.html`)

For local development, it is recommended to use a local web server (e.g., VS Code Live Server extension) to ensure all relative paths and functionalities work correctly as they would on a deployed server.

## Usage

Once you have opened the `index.html` file in your browser, you can:

1.  **Navigate:** Explore the different sections of the website using the navigation menu (likely provided by `navbar.css` and `navbar1.css`).
2.  **Learn:** Read articles, discover the association's history, and get to know the team members.
3.  **Engage:** Fill out the questionnaire or the association form to interact with the platform.
4.  **Understand:** Review the strategic plan to learn about the association's future direction.

## Testing

As a static front-end project, formal automated tests (unit, integration) are not typically implemented for this type of structure. Testing primarily involves manual inspection:

*   **Browser Compatibility:** Test the website across different web browsers (Chrome, Firefox, Edge, Safari) to ensure consistent appearance and functionality.
*   **Responsiveness:** Verify that the website layout adapts correctly to various screen sizes and devices (desktops, tablets, mobile phones).
*   **Link Validation:** Check all internal and external links to ensure they lead to the correct destinations.
*   **Form Functionality:** Test the questionnaire and association forms to ensure inputs are captured correctly (if client-side validation is implemented) and submissions work as expected (if integrated with a backend, though not evident in the provided files).
*   **Content Accuracy:** Proofread all text for typographical errors and ensure the information presented is accurate and up-to-date.
*   **JavaScript Interactivity:** Confirm that all JavaScript-driven features (e.g., navigation menus, image sliders, form validations if present) function as intended.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repository and create a pull request. You can also open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

This project is currently **Unlicensed**.

It is recommended to add a license file to specify the terms under which others can use, modify, and distribute your project. A common and permissive choice is the MIT License.

## Contact

Project Link: [https://github.com/xXmouhibXx/G.A.R.S.C](https://github.com/xXmouhibXx/G.A.R.S.C)
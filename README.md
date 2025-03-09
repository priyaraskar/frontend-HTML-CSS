Download and Open accordion.html.

Usage
Just include the HTML file in your project. The component uses the following CDN links:

Bootstrap 5 CSS & JS:

html

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" />
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
Glyphicons CSS:

html

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glyphicons-css@1.1.0/template.min.css" />
Include these in the <head> section of your HTML file, and the Bootstrap JS bundle before the closing </body> tag.

Customization
Icon Classes:

The accordion buttons use Glyphicons classes:

Default (closed): glyphicons glyphicons-plus-sign

Open state: glyphicons glyphicons-minus-sign

These classes can be adjusted if you want to use different icons from the Glyphicons library.

Color and Animation:

The CSS in this component controls all colors, animations, and layout properties. Feel free to customize:

Button background and text colors.

Icon transformation and rotation (using CSS transitions and cubic-bezier easing).

Content animations (open/close effects) defined in the keyframes.

Structure:

Modify or extend the accordion by adding more .accordion-item blocks. The structure follows Bootstrap’s accordion guidelines.

Contributing
Contributions and suggestions are welcome! Please open an issue for any major changes or feature requests before submitting a pull request.

Acknowledgments
Bootstrap 5

Glyphicons CSS

Inspiration from various CSS animation and UI design tutorials.

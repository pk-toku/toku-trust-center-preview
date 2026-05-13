# Toku Trust Center Webflow Handoff

Static Trust Center mockup and content export for Webflow implementation.

## Preview

- Trust Center mockup: https://pk-toku.github.io/toku-trust-center-preview/security-center/
- CSV content export: https://pk-toku.github.io/toku-trust-center-preview/assets/toku-trust-center-content.csv

## Webflow porting notes

The HTML intentionally includes the existing Webflow class names used on toku.com where there is an equivalent component, including:

- `top-nav-padding`, `top-nav-cta`, `nav-padding`, `mx_width`
- `nav-dropdown`, `w-dropdown`, `nav-dropdown-toggle`, `w-dropdown-toggle`
- `products-dropdown-details`, `res-dropdown-details`, `com-nav`, `w-dropdown-list`
- `dropdown-grid-column`, `dropdown-column-title`, `dropdown-column-det`
- `dropdown-link-wrap`, `dropdown-link-icon`, `w-inline-block`
- `w_600`, `tx-bold`, `cta-main`, `feature-card-2`, `article-card`

Trust Center-specific classes are kept alongside those Webflow classes so the preview renders correctly and so the new Trust Center sections remain easy to identify.

## Files

- `security-center/index.html` - main Trust Center page
- `security-center/**/index.html` - category and article pages
- `assets/styles.css` - styling for the static mockup
- `assets/toku-trust-center-content.csv` - content export for Webflow import

This is a static handoff bundle. It is not the production application.

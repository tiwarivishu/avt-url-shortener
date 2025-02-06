# AVT URL Shortener Plugin

A simple and effective WordPress plugin to shorten URLs with optional custom short codes. This plugin allows users to generate short, easy-to-share links and supports automatic redirection from short links to original URLs. Perfect for bloggers, marketers, or anyone needing quick URL shortening.

## Features
- **Instant URL shortening**: Shorten any URL with a click.
- **Custom short codes**: Create personalized short links for better branding or readability.
- **Automatic redirection**: Short URLs redirect to the original long URL seamlessly.
- **Copy to clipboard**: Copy shortened URLs easily with a button.
- **Lightweight and secure**: No database bloat, minimal security concerns.

## Installation

1. **Download** the plugin ZIP file or clone this repository.
2. **Upload** the extracted folder to the `/wp-content/plugins/` directory.
3. **Activate** the plugin from the WordPress Admin dashboard under the 'Plugins' section.
4. **Use** the `[avt_url_shortener]` shortcode to display the URL shortening form on any page or post.

## Usage

1. Navigate to the page or post where you've used the `[avt_url_shortener]` shortcode.
2. Enter the original URL that you want to shorten in the provided form.
3. Optionally, create a custom short code for the URL.
4. Click on the "Shorten URL" button to generate your short URL.
5. You can copy the short URL to your clipboard using the "Copy" button.

## Example Shortcode Usage

```php
[avt_url_shortener]

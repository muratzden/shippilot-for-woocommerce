# ShipPilot for WooCommerce

ShipPilot for WooCommerce is an independent shipping integration plugin that enables WooCommerce merchants to create shipments, generate shipping labels, synchronize tracking information and automate shipping workflows directly from the WordPress administration panel.

---

## Features

* Shipment creation
* Shipping label generation
* Shipment tracking synchronization
* Reference and shipment barcode support
* A4 / A5 shipping label printing
* ZPL label download
* WooCommerce customer notification emails
* WooCommerce HPOS compatible
* Translation ready
* Secure API communication
* Extensible developer architecture

---

## Requirements

* WordPress 6.0 or higher
* WooCommerce 7.0 or higher
* PHP 7.4 or higher

---

## Installation

1. Download the latest release.
2. Upload the `shippilot-for-woocommerce` folder to `/wp-content/plugins/`.
3. Activate the plugin from **Plugins → Installed Plugins**.
4. Open **ShipPilot** from the WordPress administration menu.
5. Configure your shipping provider API credentials.
6. Test the API connection.
7. Save your settings.

---

## Configuration

The plugin provides configuration options for:

* API credentials
* Shipping provider configuration
* Default shipment settings
* Tracking preferences
* Order automation
* Shipping label settings

---

## External Services

ShipPilot communicates with supported shipping provider APIs only when the merchant initiates a shipping operation.

### Purpose

* Create shipments
* Generate shipping labels
* Retrieve shipment tracking information
* Synchronize shipment status

### Data transmitted

* API authentication credentials
* Recipient information
* Shipment information
* Tracking requests

Only the information required to perform shipping operations is transmitted.

---

## Documentation

Documentation is available on GitHub Pages.

* Documentation
* Privacy Policy
* Terms of Service
* Support
* Changelog

https://muratzden.github.io/shippilot-for-woocommerce/

---

## Project Structure

```text
assets/
├── css/
├── js/

docs/

includes/

README.md
readme.txt
LICENSE
CHANGELOG.md
shippilot-for-woocommerce.php
```

---

## Development Goals

ShipPilot is designed with a modular architecture to support future expansion while maintaining compatibility with WordPress Coding Standards.

Planned improvements include:

* Multi-carrier architecture
* Provider abstraction layer
* Additional carrier integrations
* REST API improvements
* Performance optimizations
* Developer hooks and filters

---

## Compatibility

* WordPress Coding Standards
* WooCommerce HPOS
* WordPress Plugin Check
* Translation Ready
* GPL-2.0-or-later

---

## Contributing

Bug reports, feature requests and pull requests are welcome.

Please open an issue before submitting large changes.

---

## License

Licensed under the GNU General Public License v2.0 or later (GPL-2.0-or-later).

See the LICENSE file for details.

---

## Author

**Murat Özden**

GitHub Repository

https://github.com/muratzden/shippilot-for-woocommerce

Documentation

https://muratzden.github.io/shippilot-for-woocommerce/

---

© 2026 Murat Özden. Licensed under GPL-2.0-or-later.

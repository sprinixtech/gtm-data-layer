# Magento 2 GTM Data Layer Module - Coming Soon

The Magento 2 GTM Data Layer Module is a custom module that allows you to manage the Google Tag Manager (GTM) data layer in your Magento 2 store. It provides a flexible and extensible solution for adding data to the data layer, which can be used for various tracking and analytics purposes.

## Features

- Seamless integration with Google Tag Manager
- Easy management of data layer variables
- Customizable event-based triggers for populating the data layer
- Extensible architecture for adding additional functionality

## Requirements

- Magento 2.x
- Google Tag Manager account

## Installation

1. Clone or download this repository.
2. Extract the contents and copy the `VendorName` directory into the `app/code` directory of your Magento installation.
3. Run the following CLI commands from your Magento 2 root directory:

` bin/magento module:enable VendorName_GtmDataLayer `
` bin/magento setup:upgrade `
` bin/magento cache:clean `


4. Log in to the Magento admin panel and configure the module settings under **Stores > Configuration > GTM Data Layer**.
5. Customize the module as per your requirements by modifying the observer class and configuration files.

## Usage

1. Log in to your Google Tag Manager account and create a new container for your Magento store.
2. Obtain your Google Tag Manager container ID.
3. Log in to the Magento admin panel and navigate to **Stores > Configuration > GTM Data Layer**.
4. Enter your Google Tag Manager container ID in the provided field.
5. Configure the data layer variables and event triggers as needed.
6. Save the configuration and clear the Magento cache.
7. The module will automatically populate the data layer variables and trigger events based on your configuration.

## Customization

- coming soon

## Contribution

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request.

## License

The Magento 2 GTM Data Layer Module is open-source software licensed under the [MIT license](LICENSE).

## Support

For any issues or questions, please [open an issue](https://github.com/sprinixtech/gtm-data-layer/) on the GitHub repository.

## Disclaimer

This module is provided as-is without any warranty. Use it at your own risk.

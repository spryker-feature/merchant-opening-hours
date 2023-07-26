# Spryker Feature: Merchant Opening Hours

Merchant Opening Hours is a feature that allows a Merchant entity to have their working/opening hours saved in the system as well as it being retrievable for presentation for curious customers. A merchant can have a Weekday Schedule, meaning a daily schedule for every day of the week, as well as date-based exceptions where they setup different working/opening hours for specific dates like during the holiday season.

## Installation

```
composer require spryker-feature/merchant-opening-hours
```

## Recommended feature dependencies
- [spryker-feature/marketplace-merchant](https://github.com/spryker-feature/marketplace-merchant)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [MerchantOpeningHoursRestApi ^1.0.0](https://github.com/spryker/merchant-opening-hours-rest-api) (Legacy Glue)

# Changelog

## Version 1.3.10

_Mon 24 Jan 2022_

- Installed phpunit as a dev dependency
- Standardised non-JSON responses into JSON error objects (EIT-741)

## Version 1.3.9

_Wed 05 Jan 2022_

- Added support for PHP 8.1

## Version 1.3.8

_Tue 28 Sep 2021_

- Updated the SIGNED_32BIT_INT_MIN in Model (EIT-488)

## Version 1.3.7

_Fri 10 Sep 2021_

- Add a `merchantPortalOrderUrl` property to the Payment model ([#42](https://github.com/afterpay/sdk-php/issues/42))

## Version 1.3.6

_Thu 02 Sep 2021_

- Add a setter on the HTTP class for log obfuscation

## Version 1.3.5

_Thu 12 Aug 2021_

- Restored composer.json for dist package (EIT-312)

## Version 1.3.4

_Thu 12 Aug 2021_

- Stopped bundling tests and sample code with dist package (EIT-312)

## Version 1.3.3

_Wed 28 Jul 2021_

- Added a store URL to the end of the UA header ([#25](https://github.com/afterpay/sdk-php/issues/25))

## Version 1.3.2

_Thu 22 Jul 2021_

- Added merchant portal URLs for EU

## Version 1.3.1

_Tue 20 Jul 2021_

- Expanded Get Configuration responses to include information about:
  - Cross-Border Trade (CBT) configuration
  - Active countries (EU only)

## Version 1.3.0

_Mon 19 Jul 2021_

- Added a new feature to generate a Merchant Portal URL on Order creation
- Added support for European countries: Spain (ES), France (FR) and Italy (IT)
- Updated test workflows to separate build tests from integration tests

## Version 1.2.0

_Wed 26 May 2021_

- Added support for Express Checkout ([#10](https://github.com/afterpay/sdk-php/issues/10))

## Version 1.1.2

_Tue 25 May 2021_

- Improved endpoint coverage ([#14](https://github.com/afterpay/sdk-php/issues/14))

## Version 1.1.1

_Fri 21 May 2021_

- Improved the Consumer Simulator to also simulate 2FA ([#18](https://github.com/afterpay/sdk-php/issues/18))
- Fixed a warning that could occur when validating GET requests ([#13](https://github.com/afterpay/sdk-php/issues/13))

## Version 1.1.0

_Fri 19 Feb 2021_

- Added support for the Deferred Payment Flow
- Added a new Consumer Simulator feature for integration testing

## Version 1.0.3

_Thu 04 Feb 2021_

- Added a new feature to allow platforms to add extra details to UA header

## Version 1.0.2

_Thu 03 Dec 2020_

- Added build tests to verify compatibility with PHP 8.0

## Version 1.0.1

_Wed 28 Oct 2020_

- Performed composer updates and code linting

## Version 1.0.0

_Wed 28 Oct 2020_

- Initial release

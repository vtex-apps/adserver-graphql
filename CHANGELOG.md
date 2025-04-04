# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.6.0] - 2025-04-01

- Add SKU ID query parameter to segment ads.

## [0.5.0] - 2025-02-14

### Added
- Create query parameter `userId` and `sessionId` for `sponsoredProducts`.


## [0.4.0] - 2025-02-14

### Added

- `sellerId` to `SponsoredProduct` type.

## [0.3.1] - 2024-11-01

### Added

- `sponsoredBanners` query.
- `SponsoredBanner` type.
- `AdvertisementBanner` type.

## [0.3.0] - 2024-07-08

### Added

- `placement` input value.

## [0.2.0] - 2023-12-07

## [0.2.0] - 2023-12-05

### Added

- Created query parameter `anonymousId` for `sponsoredProducts` used on A/B testing.

## [0.1.0] - 2023-10-24

### Added

- Created the field `identifier`, which allow for different types of product identifiers such as SKU, VTEX ID and EAN.

### Changed

- Change the response type of the `sponsoredProducts` query back to an array of products, adding the `advertisment` field into it.

## [1.0.0] - 2023-09-20


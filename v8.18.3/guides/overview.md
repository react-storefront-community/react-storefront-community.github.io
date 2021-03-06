# Overview

In this guide you'll get a high-level introduction to React Storefront, what it provides, and the technologies that it uses.

## PWA

Apps built with React Storefront are progressive web apps (PWAs) by default. React Storefront automatically provides a service-worker that provides offline browsing and handles caching of both static assets and API calls.

## Built on Next.js

React Storefront is built on top of the most widely used framework in the React community, next.js. It follows the standard next.js directory structure and can be deployed to any node.js environment and many serverless environments, such as Layer0 and AWS Lambda.

## Server Side Rendering

As with all Next.js apps, server-side rendering is built in. Server-side rendering when combined with caching at edge provides the fastest initial landing experience for your users and ensures your app is search engine friendly.

## Material UI

React Storefront's components are built on top of Material UI, the most popular set of UI components in the React Community. React Storefront provides components that are common to many ecommerce apps, such as:

- Main Menu
- Navigation Tabs
- Media Carousel
- Accordion
- Color Selector
- Size Selector
- Quantity Selector
- Search

... and more!

## Built for Speed

React Storefront provides the fastest possible shopping experience by prefetching and caching linked pages before the user navigates to them, providing an "instant back" experience by saving page data in window.history.state so that it does not need to be refetched when the user navigates back.

## Built for Scale

React Storefront scales from $10M to $1B+ revenue sites and is currently being used by multiple eCommerce companies on top of the following platforms:

- Salesforce Commerce Cloud (formerly Demandware)
- Magento
- SAP Commerce Cloud (formerly SAP Hybris)
- Oracle Commerce (ATG)
- HCL Commerce (formerly IBM Websphere Commerce)
- Shopify
- BigCommerce

... and more!

## eCommerce Platform Connectors

Prebuilt eCommerce platform connectors help you get up and running as quickly as possible. The connectors that are currently open source are:

- [Magento2 Connector](https://github.com/storefront-foundation/magento2-connector)
- [Salesforce Commerce Cloud Connector](https://github.com/storefront-foundation/salesforce-commerce-cloud-connector)

More information on connectors can be found in the [Connectors guide](/guides/connectors).

# React Localization

The `@syncfusion/react-locale` package provides locale translations for Syncfusion's Essential® Studio React components, enabling seamless localization across multiple languages and regions.

## Setup

To install the `@syncfusion/react-locale` package, run the following command:

```sh
npm install @syncfusion/react-locale
```

## Supported Languages

The following languages and cultures are currently supported:

| Culture-Code | Language                       |
| ------------ | ------------------------------ |
| ar-AE        | Arabic - United Arab Emirates  |
| ar            | Arabic - Arabia               |
| cs        | Czech - Czech Republic         |
| da      | Danish - Denmark               |
| de       | German - Germany               |
| en-GB     | English - United Kingdom      |
| en-US        | English - United States        |
| es      | Spanish - Spain                |
| fa      | Farsi - Iran                   |
| fi       | Finnish - Finland              |
| fr        | French - France                |
| he       | Hebrew - Israel                |
| hr      | Croatian - Croatia             |
| hu     | Hungarian - Hungary    
| id           | Indonesian
| is     |Icelandic - Iceland             |
| it     | Italian - Italy                |
| ja     | Japanese - Japan               |
| ko     | Korean - Korea                 |
| ms      | Malay - Malaysia               |
| nb      | Norwegian (Bokmål) - Norway    |
| ne-NP   | Nepali - Nepal               |
| nl      | Dutch - The Netherlands        |
| pl      | Polish - Poland                |
| pt      | Portuguese - Portugal          |
| ro      | Romanian - Romania             |
| ru     | Russian - Russia               |
| sk     | Slovak - Slovakia              |
| sv      | Swedish - Sweden               |
| th     | Thai - Thailand                 |
| tr    | Turkish - Turkey               |
| vi     | Vietnamese - Vietnam           |
| zh       | Chinese - China                |


## Usage

### Loading Locale Data

Import the desired locale JSON file and use the `L10n.load` method to register the locale data.

```tsx
import { L10n } from '@syncfusion/react-base';
import german from '@syncfusion/react-locale/src/de.json';

L10n.load(german);
```

## Applying Locale with Provider

Wrap your application or component tree with the `Provider` component from `@syncfusion/react-base` and specify the desired locale.

```tsx
import { Provider } from '@syncfusion/react-base';
import {  NumericTextBox } from "@syncfusion/react-inputs";

<Provider locale="de">
  <NumericTextBox placeholder="Enter value" width={250} defaultValue={20} />
</Provider>
```
> This ensures that all child components respect the specified locale.

Refer to the [Localization Documentation](https://react.syncfusion.com/react-ui/common-features/localization) for detailed usage instructions and examples.

## Support

Product support is available through following mediums.

* [Support ticket](https://support.syncfusion.com/support/tickets/create) - Guaranteed Response in 24 hours | Unlimited tickets | Holiday support
* Live chat

## License and copyright

> This is a commercial product and requires a paid license for possession or use. Syncfusion’s licensed software, including this component, is subject to the terms and conditions of Syncfusion's [EULA](https://www.syncfusion.com/eula/es/). To acquire a license for [React UI components](https://www.syncfusion.com/react-components), you can [purchase](https://www.syncfusion.com/sales/products) or [start a free 30-day trial](https://www.syncfusion.com/account/manage-trials/start-trials).

> A [free community license](https://www.syncfusion.com/products/communitylicense) is also available for companies and individuals whose organizations have less than $1 million USD in annual gross revenue and five or fewer developers.

&copy; Copyright 2025 Syncfusion®, Inc. All Rights Reserved. The Syncfusion® Essential® Studio license and copyright applies to this distribution.
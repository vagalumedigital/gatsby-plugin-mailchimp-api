### Intro

This is a plugin developed to use with MailChimp API.

> Manage contacts on mailchimp. Create new contact for your audience or update a contact if exists.

### Installation

```
yarn add @vagalumedigital/gatsby-plugin-mailchimp-api
```

### Usage

`gatsby-config.js`

```javascript
[
  {
    resolve: `@vagalumedigital/gatsby-plugin-mailchimp-api`,
    options: {
      id: '<id-of-your-list>',
      key: '<MAILCHIMP-API-KEY>'
    }
  }
];
```

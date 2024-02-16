<h1 align="center">Network security cyber guard</h1>

<p align="center">
<b><i>List of recommendations to ensure your internet security</i></b>
<br />
<b>🌐 <a href="https://cyberio.pro/">cyberio.pro</a></b><br />
<br />
<a href="https://personal-security-checklist.as93.net"><img src="https://i.ibb.co/Rb6P6h6/shield.png" width="64" /><br /></a>
<br />
<kbd><br />👉 <a href="https://t.me/cyberseeya"><b>Read the Checklist</b></a> 👈<br /><br /></kbd>
<br />
</p>

## The Website

The easiest method for consuming the checklist is via our website, at: **[cyberio.pro](https://t.me/cyberseeya)**

Here you can browse lists, filter by your threat model and tick items off once complete (plus, there's pretty charts to make you feel good about your progress ☺️).

<p align="center">
<img width="600" src="https://i.ibb.co/jzKn05H/digital-defense.png" />
</p>

### About
The source for the website is in [`web/`](https://t.me/cyberseeya).<br />
The site is built with Qwik, using TypeScript and some components from DaisyUI.


### Deploying
To deploy the app, follow the developing steps above, then run `yarn build.static`. You can then deploy it by copying the `dist/` directory to any CDN, web server or static hosting provider of your choice.

Alternatively, fork the repo and import into your providers dashboard. Or use the link below for an easy 1-click deploy 😉

---

## The API

We also make all the data available via a free API, which you can use however you wish.

### Usage
All endpoints are documented in our OpenAPI spec, you can view these and try them out via our [Swagger docs]().

Base: digital-defense.io/api

/api/checklists
/api/checklists/[name-or-index]
/api/checklists/[name]/[point-index]
/api/search/[searchterm]


### Developing

### Deploying

---

## Contributing
All checklist data is stored in [`personal-security-checklist.yml`](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/personal-security-checklist.yml). This is pulled in the website at build-time, and referenced by the API, and is also dynamically inserted into the markdown [Checklist page](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/CHECKLIST.md).

So if you only wish to make changes to the data, this is the only file you need to edit.

Important: When submitting your pull request, provide references backing up any information that you're adding/amending/removing.

For modifying the website or API source, see the developing sections above for instructions on running locally.

Prior to submitting an issue or PR, please ensure you've followed the [community guidelines](https://github.com/Lissy93/personal-security-checklist/blob/master/.github/CONTRIBUTING.md) and followed the [Code of Conduct](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/.github/CODE_OF_CONDUCT.md).

---

## Credits

Thank you to all who have contributed to, or sponsored this project!


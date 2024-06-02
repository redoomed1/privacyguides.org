---
title: "Productivity Tools"
icon: material/file-sign
description: Most online office suites do not support E2EE, meaning the cloud provider has access to everything you do.
cover: productivity.webp
---
<!-- markdownlint-disable MD024 -->
Most online office suites do not support E2EE, meaning the cloud provider has access to everything you do. The privacy policy may legally protect your rights, but it does not provide technical access constraints.

## Collaboration Platforms

### Nextcloud

<div class="admonition recommendation" markdown>

![Nextcloud logo](assets/img/productivity/nextcloud.svg){ align=right }

**Nextcloud** is a suite of free and open-source client-server software for creating your own file hosting services on a private server you control.

[:octicons-home-16: Homepage](https://nextcloud.com){ .md-button .md-button--primary }
[:octicons-eye-16:](https://nextcloud.com/privacy){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://nextcloud.com/support){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/nextcloud){ .card-link title="Source Code" }
[:octicons-heart-16:](https://nextcloud.com/contribute){ .card-link title=Contribute }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=com.nextcloud.client)
- [:simple-appstore: App Store](https://apps.apple.com/app/id1125420102)
- [:simple-github: GitHub](https://github.com/nextcloud/android/releases)
- [:simple-windows11: Windows](https://nextcloud.com/install/#install-clients)
- [:simple-apple: macOS](https://nextcloud.com/install/#install-clients)
- [:simple-linux: Linux](https://nextcloud.com/install/#install-clients)

</details>

</div>

<div class="admonition danger" markdown>
<p class="admonition-title">Danger</p>

We don't recommend using the [E2EE App](https://apps.nextcloud.com/apps/end_to_end_encryption) for Nextcloud as it may lead to data loss; it is highly experimental and not production quality. For this reason, we don't recommend third-party Nextcloud providers.

</div>

### CryptPad

<div class="admonition recommendation" markdown>

![CryptPad logo](assets/img/productivity/cryptpad.svg){ align=right }

**CryptPad** is a private-by-design alternative to popular office tools. All content on this web service is end-to-end encrypted and can be shared with other users easily.

[:octicons-home-16: Homepage](https://cryptpad.fr){ .md-button .md-button--primary }
[:octicons-eye-16:](https://cryptpad.fr/pad/#/2/pad/view/GcNjAWmK6YDB3EO2IipRZ0fUe89j43Ryqeb4fjkjehE){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://docs.cryptpad.fr){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/xwiki-labs/cryptpad){ .card-link title="Source Code" }
[:octicons-heart-16:](https://opencollective.com/cryptpad){ .card-link title=Contribute }

</details>

</div>

### Criteria

**Please note we are not affiliated with any of the projects we recommend.** In addition to [our standard criteria](about/criteria.md), we have developed a clear set of requirements to allow us to provide objective recommendations. We suggest you familiarize yourself with this list before choosing to use a project, and conduct your own research to ensure it's the right choice for you.

#### Minimum Requirements

In general, we define collaboration platforms as full-fledged suites which could reasonably act as a replacement to collaboration platforms like Google Drive.

- Open source.
- Makes files accessible via WebDAV unless it is impossible due to E2EE.
- Has sync clients for Linux, macOS, and Windows.
- Supports document and spreadsheet editing.
- Supports real-time document collaboration.
- Supports exporting documents to standard document formats (e.g. ODF).

#### Best-Case

Our best-case criteria represents what we would like to see from the perfect project in this category. Our recommendations may not include any or all of this functionality, but those which do may rank higher than others on this page.

- Should store files in a conventional filesystem.
- Should support TOTP or FIDO2 multi-factor authentication support, or passkey logins.

## Paste services

### PrivateBin

<div class="admonition recommendation" markdown>

![PrivateBin logo](assets/img/productivity/privatebin.svg){ align=right }

**PrivateBin** is a minimalist, open-source online pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256-bit AES. It is the improved version of ZeroBin.

[:octicons-home-16: Homepage](https://privatebin.info){ .md-button .md-button--primary }
[:octicons-server-16:](https://privatebin.info/directory){ .card-link title="Public Instances"}
[:octicons-info-16:](https://github.com/PrivateBin/PrivateBin/wiki/FAQ){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/PrivateBin/PrivateBin){ .card-link title="Source Code" }

</div>

### Criteria

**Please note we are not affiliated with any of the projects we recommend.** In addition to [our standard criteria](about/criteria.md), we have developed a clear set of requirements to allow us to provide objective recommendations. We suggest you familiarize yourself with this list before choosing to use a project, and conduct your own research to ensure it's the right choice for you.

#### Minimum Requirements

- Must be open source.
- Must implement "zero-trust" end-to-end encryption.
- Must support password-protected files.

#### Best-Case

Our best-case criteria represents what we would like to see from the perfect project in this category. Our recommendations may not include any or all of this functionality, but those which do may rank higher than others on this page.

- Should have a published audit from a reputable, independent third-party.

## Language services

### LanguageTool

<div class="admonition recommendation" markdown>

![LanguageTool logo](assets/img/productivity/languagetool.svg#only-light){ align=right }
![LanguageTool logo](assets/img/productivity/languagetool-dark.svg#only-dark){ align=right }

**LanguageTool** is a multilingual grammar, style and spell checker that supports more than 20 languages. The software is [self-hostable](https://dev.languagetool.org/http-server), and the extensions do not send your input text to their server.

  LanguageTool offers integration with a variety of [office suites](https://languagetool.org/services#text_editors) and [email clients](https://languagetool.org/services#mail_clients).

[:octicons-home-16: Homepage](https://languagetool.org){ .md-button .md-button--primary }
[:octicons-eye-16:](https://languagetool.org/legal/privacy){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://languagetooler.freshdesk.com/en/support/solutions){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/languagetool-org){ .card-link title="Source Code" }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-appstore: App Store](https://apps.apple.com/app/id1534275760)
- [:simple-windows11: Windows](https://languagetool.org/windows-desktop)
- [:simple-apple: macOS](https://languagetool.org/mac-desktop)
- [:simple-firefoxbrowser: Firefox](https://addons.mozilla.org/firefox/addon/languagetool)
- [:simple-googlechrome: Chrome](https://chrome.google.com/webstore/detail/grammar-and-spell-checker/oldceeleldhonbafppcapldpdifcinji)
- [:simple-microsoftedge: Edge](https://microsoftedge.microsoft.com/addons/detail/hfjadhjooeceemgojogkhlppanjkbobc)
- [:simple-safari: Safari](https://apps.apple.com/app/id1534275760)

</details>

</div>

### Criteria

**Please note we are not affiliated with any of the projects we recommend.** In addition to [our standard criteria](about/criteria.md), we have developed a clear set of requirements to allow us to provide objective recommendations. We suggest you familiarize yourself with this list before choosing to use a project, and conduct your own research to ensure it's the right choice for you.

- Must be open source.
- Must be possible to self-host.

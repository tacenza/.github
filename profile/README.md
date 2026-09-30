<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/header-light.svg">
  <img alt="TACENZA. by CARTIQO. Private messages. Just a username and a password." src="./assets/header-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.tacenza.app"><b>Website</b></a> ·
  <a href="https://chat.tacenza.app">TACENZA Chat</a> ·
  <a href="https://docs.tacenza.app">Documentation</a> ·
  <a href="https://support.tacenza.app">Help Center</a> ·
  <a href="https://blog.tacenza.app">Blog</a> ·
  <a href="https://status.tacenza.app">Status</a>
</p>

TACENZA is an end-to-end encrypted messenger for chats, groups and whole communities – and private email is on the way. Only you and the people you write to can read what you send. Not even we can.

> **New:** Username claims are open. [Claim yours](https://chat.tacenza.app/) before someone else does – it takes a username and a password. [Read the announcement](https://blog.tacenza.app/articles/claims-are-open).

## The TACENZA products

Everyday conversations, without a platform reading along. TACENZA Chat is here today. TACENZA Mail is in development. Both are built on the same rule: collect as little as possible, and say plainly what's collected.

| | | |
|---|---|---|
| **[TACENZA Chat](https://www.tacenza.app/products/chat)** | Available | End-to-end encrypted chats, groups and communities, on the web and Windows. |
| **[TACENZA Mail](https://www.tacenza.app/products/mail)** | In development | Private email for you, your team and your own domain. |
| **[TACENZA Store](https://tacenza.store)** | Available | The official TACENZA shop. |

### TACENZA Chat

The groups and chats you know, without the platform that reads them. Everything you'd expect from a modern messenger – for friends, clubs, interest communities and small teams. Every feature is built so the server stays blind.

| | |
|---|---|
| **Messaging** | Replies, reactions, edits, pins, threads, voice messages, photos, files and events – in one-to-one chats and groups. |
| **Groups and communities** | Channels with categories, private channels with their own keys, and no member limit on any plan. |
| **Roles and moderation** | Owners, admins and custom roles with per-member permissions, invite links with approval, slow mode, timeouts and bans. |
| **Profiles** | A profile with a name, picture and bio, where you choose who sees each field. |
| **Discover** | A public directory for communities that want to be found. Listing is always the group's choice. |
| **Notifications** | Opt-in push notifications that carry no content: your device fetches and decrypts the message itself. |
| **Disappearing messages** | From 5 minutes to 7 days, per chat, with delete for everyone. |
| **Bots** | Build bots in Bot Studio and run them with the Bot API and the `@tacenza/bot` SDK for Node.js. |

**[Open TACENZA Chat](https://chat.tacenza.app/)** · [See everything in Chat](https://www.tacenza.app/products/chat)

### TACENZA Mail

*In development – sign-up isn't open yet.*

Business email that keeps to itself: private email for you, your team and your own domain. It isn't end-to-end encrypted, and we'd rather tell you that than pretend otherwise. What's built so far:

- **Inbox and folders** – folders with unread counts, a clean reader, and HTML mail that's sanitised with remote images off.
- **Shared addresses** – addresses like support@ and billing@ that your team shares, with messages assigned to one person.
- **Your own domain** – mail on a domain you own, signed with DKIM and checked with SPF and DMARC.
- **Zero-access encryption** – optional encryption of stored mail in your browser, so our server can't read what it keeps.

## Security and privacy

Built to know as little about you as possible. Privacy isn't a setting or a paid extra. It's how TACENZA is built – and where it has limits, they're written down.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/principles-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/principles-light.svg">
  <img alt="A username and a password. Encrypted on your device. The server is blind. No tracking. Protected chats. Honest about limits." src="./assets/principles-light.svg" width="100%">
</picture>

### Don't take our word for it

For every release, our build pipeline publishes the SHA-256 of the app's code in [tacenza/releases](https://github.com/tacenza/releases), apart from the servers that run TACENZA. Hash what your browser is served and compare:

```bash
# Compare with bundle-hash.txt in the latest release
curl -s https://chat.tacenza.app/assets/<file> | sha256sum
```

[How to verify the app](https://docs.tacenza.app/security/verify-the-app) · [How security works](https://www.tacenza.app/security) · [What the server stores](https://docs.tacenza.app/security/what-we-store)

### Honest about limits

> **Nobody can reset your password – not even TACENZA.** Your device makes a recovery key when you sign up and shows it once; with it you can set a new password yourself. Keep it somewhere safe, because nobody else can open your account.

- The server knows who is in which group, because it has to enforce roles and permissions. It can't read group names, messages or profiles.
- A web page can't block screenshots. The Windows app can.
- TACENZA Mail isn't end-to-end encrypted. Zero-access encryption of stored mail is optional.
- A security review of Chat is planned before 1.0, and forward secrecy after it. Until then, the known limits are written down.

## Pricing

Plans buy capacity, never privacy. Free is fully usable and just as private: encryption, protected chats, disappearing messages and safety numbers are the same on every plan.

| | **Free** | **Plus** | **Pro** |
|---|---|---|---|
| **Price** | €0, forever | €4.99 a month, or €49.99 a year | €9.99 a month, or €99.99 a year |
| **Storage** | 1 GB | 5 GB | 15 GB |
| **Attachments** | Up to 25 MB | Up to 100 MB | Up to 500 MB |
| **Devices at once** | 2 | 5 | 10 |
| **Active bots** | 1 | 3 | 10 |
| **Priority support** | – | – | Yes |

No card needed for Free. TACENZA Mail, bundles and Business plans for organisations are on the way. [Compare every plan in detail](https://www.tacenza.app/pricing).

## One TACENZA account

*Planned.* Today TACENZA Chat and TACENZA Mail each have their own account and settings, because Chat's account keys never leave your device. Next, one TACENZA account that signs you in to every product – without our server ever seeing your password.

## Where TACENZA is today

TACENZA is made by CARTIQO for privacy-minded people and communities, starting in Denmark and the EU. The apps work in English and Danish, and Danish is never an afterthought.

- **TACENZA Chat** is working towards 1.0: an installable web app, a Windows desktop app and our own backend. Usernames can be claimed now.
- **TACENZA Mail** is in development. The first parts are built – shared addresses, encryption, team settings – and sign-up opens when it's ready.

**[Get started – it's free](https://chat.tacenza.app/)** · [Read the documentation](https://docs.tacenza.app/getting-started/create-account) · [Contact us](https://support.tacenza.app/contact)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/divider-light.svg">
  <img alt="" src="./assets/divider-light.svg" width="100%">
</picture>

<br>
<br>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/tacenza-lockup-reversed.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/tacenza-lockup.svg">
    <img alt="TACENZA. by CARTIQO." src="./assets/tacenza-lockup.svg" width="220">
  </picture>
</p>

<p align="center"><sub>TACENZA. is a CARTIQO. product.</sub></p>

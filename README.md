# PR Focus for Bitbucket — Privacy Policy

_Last updated: October 9, 2026_

PR Focus for Bitbucket is a browser extension for self-hosted Bitbucket Data Center and Server. This policy explains what data the extension accesses and how it is handled.

## What the extension accesses

The extension works only with the Bitbucket address and repositories you enter on its settings page, and only after you grant access to that address. When you open the pull request list of one of those repositories, the extension reads from your Bitbucket server, using your existing Bitbucket session:

- pull requests of the repository: titles, authors, reviewers, approval status, merge checks, build statuses;
- code owners of pull requests, if the code owners plugin is installed;
- comments, replies and reactions on pull requests in the repository;
- your Bitbucket username and display name.

This data is used only to group the pull request list into sections and to show the activity sidebar on the page.

## What the extension stores

In your browser's extension storage only:

- your settings: the Bitbucket address and repositories, whether sections are on and which sections are collapsed;
- which activity events you have marked as read;
- a short-lived cache of pull request merge statuses and your Bitbucket profile, to avoid repeated requests.

The data does not leave your browser and is removed when you uninstall the extension.

## What the extension sends

- Requests only to the Bitbucket address you configured, on your behalf, with your existing session.
- Replies to comments and reactions are posted to Bitbucket only when you explicitly send them from the sidebar.

The extension does not send data to any other server. It has no analytics, tracking, advertising or remote code. No data is sold or shared with third parties.

## Contact

Questions about this policy: use the developer contact email on the extension's Chrome Web Store page.

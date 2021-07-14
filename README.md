# Parakeet

Parakeet is an open-source technology stack for use by non-profit organizations and groups.

The name derives from parakeet, a curious and talkative bird.

## What does it do?

The goal of Parakeet is to provide organizations with an ethical, secure, and user-friendly alternative to existing technology suites from the likes of Google, Microsoft, Slack, Facebook, Discord, Zoom, etc.

Parakeet provides your organization with **video calling**, end-to-end encrypted **chat**, **social networking**, **video hosting**, and **microblogging** capabilities. It's a place where your org members and teammates can gather, coordinate, publish, and engage with a wider community. 

By integrating various free and open-source software packages, Parakeet keeps your organization's infrastructure costs down, so that you can focus your budget on more important things.

## What's in the stack?

The technology stack consists entirely of trusted and well-supported open-source applications. The configuration of these components can be customized to your needs.

### Basic stack

* Federated social media + microblogging provided by [GoToSocial](https://github.com/superseriousbusiness/gotosocial).
* End-to-end encrypted chat space, with multiple room + group capability, provided by [Matrix.org's](https://matrix.org/) [Synapse](https://matrix.org/docs/projects/server/synapse).
* Cutting edge video conferencing by [Jitsi](https://jitsi.org/).
* A landing web-page for your organization's hub, composed with [Hugo](https://gohugo.io/).
* Admin UI for managing registrations and accounts.

### Extended stack

Basic stack plus:

* Private email server from [Docker Mailserver](https://github.com/docker-mailserver/docker-mailserver).
* Calendar server provided by [Davical](https://davical.org/).
* Federated video hosting + sharing provided by [Peertube](https://joinpeertube.org/).

## How does it work?

TODO

## I want it. How do I get it?

### Self-hosting

Parakeet uses [Ansible](https://www.ansible.com/) and [Docker](https://www.docker.com/) for deployment. It is automated, but still requires some technical know-how for a proper self-hosted deployment.

For step-by-step deployment introductions, [see the documentation](some-link-to-documentation).

### Hosted services

Parakeet is also offered as a hosted service, which means that we can deploy, maintain, manage, and update it for you! Then all you have to do is administrate it.

For details on our hosting services and pricing, see [here](some-link-to-a-website)

## Contact

TODO

## License

Parakeet itself uses the [MIT License](LICENSE) to cover its aggregation of open-source components, as well as the playbooks and scripts for their deployment.

Individual components aggregated and/or used by Parakeet have separate licenses, listed here:

* Davical, [GPL3](https://www.gnu.org/licenses/gpl-3.0.html)
* Docker Mailserver, [MIT](https://github.com/docker-mailserver/docker-mailserver/blob/master/LICENSE)
* Docker OpenLDAP, [MIT](https://github.com/osixia/docker-openldap/blob/master/LICENSE)
* Element, [Apache 2.0](https://github.com/vector-im/element-web/blob/develop/LICENSE)
* GoToSocial, [AGPL3](https://github.com/superseriousbusiness/gotosocial/LICENSE)
* Hugo, [Apache 2.0](https://github.com/gohugoio/hugo/blob/master/LICENSE)
* Jitsi Meet, [Apache 2.0](https://github.com/jitsi/jitsi-meet/blob/master/LICENSE)
* Jitsi Videobridge, [Apache 2.0](https://github.com/jitsi/jitsi-videobridge/blob/master/LICENSE)
* OpenLDAP, [OpenLDAP Public License](https://www.openldap.org/software/release/license.html)
* Peertube, [AGPL3](https://github.com/Chocobozzz/PeerTube/blob/develop/LICENSE)
* Synapse, [Apache 2.0](https://github.com/matrix-org/synapse/blob/develop/LICENSE)

# gage
Gage.app - Fast, secure, distributed, decentralized & everlasting [InterPlanetary](https://ipfs.io/) storage. An app, service, API and CLI.

Based on the [IPFS](https://github.com/ipfs) Network, it will be completely distributed and decentralized.
Some progress has been done privately, but all the parts will be available as open source.

Those are not just buzzwords. It can be a reality. Mostly no one will be able to enforce control on us or our users, since we'll be on a completely serverless environment and hosting the service/app on IPFS. Every user profile will be its own separate (PWA) web app, again hosted on IPFS. We are saying "mostly" here, because we need to rely on external APIs - for example, the user authentication, and the second thing is that our API for developers will be hosted on a serverless environment (the [@zeit](https://github.com/zeit)'s [Now](https://now.sh)) behind global CDN, so we need to comply to their terms and policies. Meaning if someone wants to control us or enforce something on us, can contact our partners (Zeit, [@Okta](https://okta.com) or CloudFlare) to shut down or limit the access to our own or their APIs.

Technology stack will be [Node.js](https://nodejs.org), [UppyJS](https://uppy.io), [Tus.io](https://tus.io), [React](https://reactjs.org), [GatsbyJS](https://gatsbyjs.org), [IPFS](https://ipfs.io) and probably [GunDB](https://github.com/amark/gun).

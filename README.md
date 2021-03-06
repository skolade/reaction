#Reaction
[![Circle CI](https://circleci.com/gh/reactioncommerce/reaction.svg?style=svg)](https://circleci.com/gh/reactioncommerce/reaction)
[![Gitter](https://badges.gitter.im/JoinChat.svg)](https://gitter.im/reactioncommerce/reaction?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The Reaction commerce platform uses a reactive, real-time architecture and design approach that provides a modern commerce experience for the shopper, administrator, and developer equally.

Reaction is a Meteor application built with Meteor, Node.js, MongoDB, Javascript and CoffeeScript.

See: [Package Repository for Reaction] (https://atmospherejs.com/?q=reactioncommerce)

##Installation
```
Node.js and NPM are required. Install from http://nodejs.org/
```
To install Meteor + Reaction, and start the latest release:

```bash
curl https://install.meteor.com | /bin/sh
git clone https://github.com/reactioncommerce/reaction.git
cd reaction && git checkout master
meteor
```

There is also an executable shell [script that you can run](https://github.com/reactioncommerce/reaction/blob/development/bin/install). Additional installation options are in the [developer documentation](https://github.com/reactioncommerce/reaction-core/blob/development/docs/installation.md).

*Note: for Windows installation you also need:*

- OpenSSL
- Visual Studio 2008 redistributables
- Git + mysgit
- ImageMagick
- Python 2.7.x



##Demonstration

You can create a sandbox shop at [reactioncommerce.com](https://reactioncommerce.com). These test shops help us gather feedback for Reaction development, as well as testing PaaS deployment approaches.

*Note: These are test shops, and not for production, and are not persistent.*

##Status

**Current status: Alpha**

Currently good for contributing/observing progress, testing. It goes without saying that we're constantly refactoring, even things that are functionally done. We do not recommend using for production usage yet, unless you are very comfortable with the code, and aren't risk averse. There are still many parts in development!

The Docker image is automatically built at the [Ongo Works public Docker repo](https://index.docker.io/u/ongoworks/), on any `master` repository changes. We're working on functionality to allow selectable Reaction/Docker images in the future.

##Roadmap
As with all development, some items are ahead of schedule, and some are not. Here's how to get the details:

For a high level review our roadmap, take a look at the vision page [Reaction Vision](http://reactioncommerce.com/vision)

For grouping of development channels by feature see [the project milestones]( https://github.com/reactioncommerce/reaction/milestones
 ).

Finally for the kanban-esque, hardcore real time progress view, take a look our [waffle board](https://waffle.io/reactioncommerce/reaction)

##Feedback
Best way to provide feedback and get involved is to use the GitHub issues on the [Reaction](https://github.com/reactioncommerce/reaction) project.

>  Join us on our [Gitter chat room](https://gitter.im/reactioncommerce/reaction) to discuss, communicate, and share community support.


##Core Vision

* Fast, clean, and easy to use for end users as well as store owners.
* Full functionality / matching feature sets that you would expect from Magento, Shopify, Spree, etc.
* A focus on marketing - it's easy to have products, order processing and customer records. Translating that to conversions and traffic are often the difficult component.
* Leveraging data from social networks, and Reaction itself to present actionable merchandising data
* Limited separation of administrative functionality and "front end". Same template should be used to edit/create/read views.
* Realtime data,statistics and event tracking built in from the beginning throughout, and provide actionable information.
* As modular as possible so that any package can be customized/overwritten - i.e.: need a special order processing process, then override/extend the default
* Core packages to enable site should be a simple and generic as possible, layering complexity by adding packages through a package store ('app store') approach
* Common marketing and SEO practices should be fundamental core features
* UI/UX should be as intuitive as possible, rethinking traditional methods (adding a product should be as easy as buying one)
* Pages/routes only used when user would potentially share/bookmark
* Realtime synchronization across platforms/browsers
* Cross platform, responsive focus - should work well natively, without native apps.
* Migration paths from existing commerce platforms (Magento, Shopify, BigCommerce)
* reactioncommerce:core package can be used as a package in meteor applications
* Designer and developer friendly!
    * HTML/CSS/Javascript or CoffeeScript knowledge should be sufficient for customization. *ES6 / ECMAScript 2015 migration in the near future.*
    * Commercial package and theme development encouraged.
    * All contributors should be rewarded. [please contact us](mailto:hello@ongoworks.com)


#Developer Documentation

[Getting started guide](http://thoughts.reactioncommerce.com/how-to-get-involved-with-reaction-commerce/)

[Installation](https://github.com/ongoworks/reaction-core/blob/master/docs/installation.md)

[Guidelines](https://github.com/ongoworks/reaction-core/blob/master/docs/conventions.md)

[Methods](https://github.com/ongoworks/reaction-core/blob/master/docs/methods.md)

[Package Development](https://github.com/ongoworks/reaction-core/blob/master/docs/packages.md)

[Theme Development](https://github.com/ongoworks/reaction-core/blob/master/docs/themes.md)

[i18n Translations](https://github.com/ongoworks/reaction-core/blob/master/docs/i18n.md)

[Template Development](https://github.com/ongoworks/reaction-core/blob/master/docs/templates.md)


##Code Repositories
Hey! Where's all the code!? Most of it is in the [reaction-core](https://github.com/reactioncommerce/reaction-core/) package...

We welcome pull requests to the latest `development` version branch.

##Reaction Team
Reaction is a project of [Ongo Works](http://ongoworks.com). We also have some light reading on our [blog](http://thoughts.reactioncommerce.com/), for those curious about who we are.

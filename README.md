# Void

A starter app template for [Meteor](http://meteor.com) using [IronRouter](https://github.com/EventedMind/iron-router).

Void is based on [Telescope](http://telesc.pe) (an open-source social news app) and is bought to you by the [Discover Meteor](https://www.discovermeteor.com) team. 

## Installation

Void is ready to go. Just clone it locally, run it with `mrt`, and start coding!

## Features

- Client-side routing
- Publications/subscriptions
- Basic permissions
- Common templates

## Principles

Void adopts a modular approach, where code is broken down in different files rather than all kept in one place. As an example, Void  uses the “template/mapper” pattern, where the `item.html` template has a similarly named `item.js` JavaScript file that holds its helper code. 

Void uses the `Items` collection as an example, but you would probably replace this with your own collection name (`Posts`, `Sales`, `Projects`, etc.) and change the file and variables names accordingly. 

## File Structure

- **client**
	- **CSS**
	- **helpers**
		- handlebars.js
		- router.js
	- **views**
		- **common**
			- footer.html
			- header.html
			- layout.html
			- loading.html
			- notFound.html
		- **items**
			- item.html
			- item.js
			- items.html
		- **pages**
			- homepage.html
	- main.html
	- main.js
- **collections**
	- items.js
- **lib**
	- helpers.js
	- permissions.js
- **packages**
	- iron-router
	- sample-package
- **public**
- **server**
	- fixtures.js
	- publications.js
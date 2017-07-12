# strophe.caps.js

Plugin for [strophe.js](https://www.npmjs.com/package/strophe.js) to provide XMPP Entity Capabilities ([XEP-0115]( http://xmpp.org/extensions/xep-0115.html)).

## Usage

### Adding features

    connection.caps.add( "myfeature" );

### Removing features

    connection.caps.remove( "myfeature" );

### Sending presence

    conncection.caps.pres( attrs );

See [strophe.disco.js](https://github.com/strophe/strophejs-plugin-disco) for more info.

## Authors

- Markus Kohlhase
- [Michael Weibel](http://github.com/mweibel)

## Legacy

An older version of this plugin is included in this package `/strophe.CAPS.js`, build from CoffeScript. This is no longer maintained and will likely be removed in the future.

<a name="v0.2.2"></a>
### v0.2.2 (2013-08-31)


#### Features

* **data:** add AngularJS 1.0.8 ([72e44f01](http://github.com/passy/google-cdn/commit/72e44f0121153942a9b77b987c1c3570474ad2d5))

<a name="v0.2.1"></a>
### v0.2.1 (2013-08-11)


#### Bug Fixes

* **cdnify:** strip leading slashes ([4e01423f](http://github.com/passy/google-cdn/commit/4e01423fb22451f2df95c7d74c071b30d9585c31))


#### Features

* **data:** dojo, swfobject for google CDN ([bdb5c3b7](http://github.com/passy/google-cdn/commit/bdb5c3b7b848d842bea401007c13dee8175b3299))

<a name="v0.2.0"></a>
## v0.2.0 (2013-08-11)


#### Bug Fixes

* **data:** filter out invalid semvers ([1c3552e9](http://github.com/passy/google-cdn/commit/1c3552e9acb97aecbb9128eab9bc448385e1bf81))


#### Features

* **cdnify:**
  * run bower lookups in parallel ([00a1c9ce](http://github.com/passy/google-cdn/commit/00a1c9ceb9d6baeaa2a761cd4cdc83875f70b1f2))
  * change to asynchronous API ([17ea90ce](http://github.com/passy/google-cdn/commit/17ea90ce0249606e28036ba249438916d41a84f9))
  * preparations for multi-cdn support ([5a73bea0](http://github.com/passy/google-cdn/commit/5a73bea017456d97ccedce241853e82010720bb3))
* **data:**
  * full heuristic cdnjs support ([d6e9830c](http://github.com/passy/google-cdn/commit/d6e9830c494c3bcc02c39beaf4566ceee88779f2))
  * add cdnjs support for jquery ([eb215d9d](http://github.com/passy/google-cdn/commit/eb215d9d7a66a6a57c3673844ee41b4010ac8398))
* **util:** add bower main resolver ([104e1aa2](http://github.com/passy/google-cdn/commit/104e1aa28bc800ff3980f01df557044e29dee332))


### Breaking Changes

* `googlecdn` is no longer synchronous and requires a callback
* Hoisting is no longer supported. If you relied on this, please get in touch.
  It looked like nobody would be using it.

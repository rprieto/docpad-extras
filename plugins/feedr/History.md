## History

- v2.0.1 July 8, 2012
	- Removed underscore dependency
	- Fixed path exists warning
	- Will now store cached files inside the operating systems actual tmp path, instead of always assuming it is `/tmp`
		- Customisable by the `tmpPath` configuration option

- v1.0.0 April 14, 2012
	- Updated for DocPad v5.0

- v0.2.0 April 6, 2012
	- Now exposes `@feedr.feeds` to the `templateData` instead of `@feeds`

- v0.1.0 March 23, 2012
	- Initial working version for [Benjamin Lupton's Website](https://github.com/balupton/balupton.docpad)
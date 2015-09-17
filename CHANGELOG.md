Changelog
=========

* 1.0.0-next (@release_date@)

 * renamed `Input` and implementations to `InputStream`
 * renamed `Output` and implementations to `OutputStream`
 * turned `IO` into a class
 * added `Input`
 * added `Output`
 * added `isClosed()` to `InputStream` and `OutputStream`
 * removed `RawIO` and `FormattedIO`
 * changed constructor of `BufferedIO`
 * changed constructor of `ConsoleIO`
 
* 1.0.0-beta3 (2015-08-24)

 * fixed minimum versions in composer.json

* 1.0.0-beta2 (2015-05-28)

 * fixed `Paragraph` to not indent empty lines
 * added `RawArgs::getScriptName()` and `Args::getScriptName()`
 * enabled nice exception rendering for exceptions thrown before the IO is created
 * made it possible to pass a callable to `ConsoleApplication::__construct()`

* 1.0.0-beta (2015-03-19)

 * first release
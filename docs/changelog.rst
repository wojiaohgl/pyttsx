Changelog
---------

Version 1.2
~~~~~~~~~~~

* Added pip install instructions to doc.
* Fixed voice selection to use VoiceLocaleIdentifier on OS X instead of deprecated VoiceLanguage
* Fixed voice selection to use VoiceLocaleIdentifier on OS X instead of deprecated VoiceLanguage
* Introduced speakToFile function to driver api to write speech direct to disk as audio file. Support for OS X
* Written speech direct to disk as audio file for windows. windows SAPI does not support events http://msdn.microsoft.com/en-us/library/ms723597(v=vs.85).aspx

Version 1.1
~~~~~~~~~~~

* Fixed compatibility with pip
* Fixed espeak crash when running on Natty (https://github.com/parente/pyttsx/issues/3)

Version 1.0
~~~~~~~~~~~

First release
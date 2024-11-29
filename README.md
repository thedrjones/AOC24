# AOC24
[Advent of Code 2024](https://adventofcode.com/2024), in [InterSystems ObjectScript](https://docs.intersystems.com/irislatest/csp/docbook/DocBook.UI.Page.cls?KEY=PAGE_objectscript) 

My code will mostly compatible with other MUMPS implementation, because that's my background. You'll need to add and use your own functions to replace some the built-in Cache/IRIS specific ones (e.g. ZSTRIP, ZCVT/ZCONVERT and any ##class lazyness) if you're using something else.

I won't always do it on the day it was set for, some days I may skip because I get annoyed, or get distracted by real life! There are likley to be a lot of distractions this year, there is more than usual going on.

Eventually I'll give up, it always happens.
Although looking around, we can apparantly [embed python](https://docs.intersystems.com/irislatest/csp/docbook/DocBook.UI.Page.cls?KEY=AFL_epython), we don't have that in the version I use the in the day job ... but it could be an easier way out of a very hard problem in a particularly hard task to think through.

I use the InterSystems IRIS Community Edition (2024.3), deployed via Docker, with a [durable](https://docs.intersystems.com/irislatest/csp/docbook/DocBook.UI.Page.cls?KEY=AFL_containers#AFL_containers_durable) database directory. For my editor, I use Visual Studio Code with the [InterSystems ObjectScript](https://marketplace.visualstudio.com/items?itemName=intersystems-community.vscode-objectscript) extension pack.
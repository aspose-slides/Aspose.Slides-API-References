---
title: interruption_token property
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token tulajdonság
Az a token, amely a megszakítási kérések figyelésére szolgál.

            Ez a token kezeli a teljes [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példány életciklusát. Bármely hosszú ideig futó művelet, például a prezentáció betöltése vagy mentése, a [`IInterruptionTokenSource`](/slides/python-net/hu/aspose.slides/iinterruptiontokensource) [`IInterruptionTokenSource.interrupt`](/slides/python-net/hu/aspose.slides/iinterruptiontokensource/interrupt) metódusának meghívásával lesz megszakítva.

### Definíció:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### Lásd még
* osztály [`IInterruptionTokenSource`](/slides/python-net/hu/aspose.slides/iinterruptiontokensource)
* osztály [`ILoadOptions`](/slides/python-net/hu/aspose.slides/iloadoptions)
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)
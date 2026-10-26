---
title: interruption_token property
second_title: Aspose.Slides a Pythonhoz a .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token tulajdonság
Az a token, amely a megszakítási kérések monitorozására szolgál.

Ez a token kezeli a teljes [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példány életciklusát. Bármely hosszú ideig futó művelet, például a prezentáció betöltése vagy mentése, a [`InterruptionTokenSource.interrupt`](/slides/python-net/hu/aspose.slides/interruptiontokensource/interrupt) metódus meghívásával lesz megszakítva a [`InterruptionTokenSource`](/slides/python-net/hu/aspose.slides/interruptiontokensource)-ban.

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
* osztály [`InterruptionTokenSource`](/slides/python-net/hu/aspose.slides/interruptiontokensource)
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* osztály [`LoadOptions`](/slides/python-net/hu/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)
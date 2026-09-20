---
title: interruption_token property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token egenskap
Token för att övervaka avbrottsförfrågningar.
            
            Denna token hanterar hela [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-instansens livslängd. Alla långvariga operationer, såsom inläsning eller sparande av presentation, avbryts genom att anropa [`InterruptionTokenSource.interrupt`](/slides/python-net/sv/aspose.slides/interruptiontokensource/interrupt)-metoden för [`InterruptionTokenSource`](/slides/python-net/sv/aspose.slides/interruptiontokensource).

### Definition:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### Se även
* klass [`InterruptionTokenSource`](/slides/python-net/sv/aspose.slides/interruptiontokensource)
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* klass [`LoadOptions`](/slides/python-net/sv/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)
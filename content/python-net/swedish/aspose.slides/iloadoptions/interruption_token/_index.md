---
title: interruption_token property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token egenskap
Token för att övervaka avbrotts-begäranden.
            
            Detta token hanterar hela [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-instansens livslängd. Alla långvariga operationer, såsom laddning eller sparning av presentation, avbryts genom att anropa [`IInterruptionTokenSource.interrupt`](/slides/python-net/sv/aspose.slides/iinterruptiontokensource/interrupt)-metoden i [`IInterruptionTokenSource`](/slides/python-net/sv/aspose.slides/iinterruptiontokensource).

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
* klass [`IInterruptionTokenSource`](/slides/python-net/sv/aspose.slides/iinterruptiontokensource)
* klass [`ILoadOptions`](/slides/python-net/sv/aspose.slides/iloadoptions)
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)
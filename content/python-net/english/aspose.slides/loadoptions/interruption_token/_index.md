---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/loadoptions/interruption_token/
weight: 80
---


## interruption_token property
The token to monitor for interruption requests.
            
            This token manages the whole [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as loading 
            or saving of presentation, will be interrupted via calling of the [`InterruptionTokenSource.interrupt`](/slides/python-net/aspose.slides/interruptiontokensource/interrupt) method of 
            the [`InterruptionTokenSource`](/slides/python-net/aspose.slides/interruptiontokensource).

### Definition:
```python
@property
def interruption_token(self):
    ...
@interruption_token.setter
def interruption_token(self, value):
    ...
```

### See Also
* class [`InterruptionTokenSource`](/slides/python-net/aspose.slides/interruptiontokensource)
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

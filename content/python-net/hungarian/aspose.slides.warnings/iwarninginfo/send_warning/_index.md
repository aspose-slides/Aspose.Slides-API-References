---
title: send_warning method
second_title: Aspose.Slides a Pythonhoz .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.warnings/iwarninginfo/send_warning/
weight: 10
---
## send_warning(self, receiver) {#iwarningcallback}
Ha a receiver nem None, akkor figyelmeztetést küld egy megadott receivernek, és dobja az
            AbortRequestedException kivételt, ha a receiver úgy dönt, hogy megszakítja a műveletet.

```python
def send_warning(self, receiver):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| receiver | [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback) | Receiver objektum [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback) |

### Lásd még
* osztály [`IWarningCallback`](/slides/python-net/hu/aspose.slides.warnings/iwarningcallback)
* osztály [`IWarningInfo`](/slides/python-net/hu/aspose.slides.warnings/iwarninginfo)
* modul [`aspose.slides.warnings`](/slides/python-net/hu/aspose.slides.warnings)
* könyvtár [`Aspose.Slides`](/slides/python-net)
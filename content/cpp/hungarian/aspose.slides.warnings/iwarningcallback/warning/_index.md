---
title: Warning()
second_title: Aspose.Slides C++ API referenciája
description: Visszahívási metódus, amely figyelmeztetést kap, és eldönti, hogy a műveletet megszakítani kell-e.
type: docs
weight: 1
url: /hu/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) metódus


Visszahívási metódus, amely figyelmeztetést kap, és eldönti, hogy a műveletet megszakítani kell-e.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Feldolgozandó figyelmeztetés. |

### Visszatérési érték

Megszakítási döntés [ReturnAction](../../returnaction/).

## Lásd még

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IWarningInfo](../../iwarninginfo/)
* Osztály [IWarningCallback](../)
* Névtér [Aspose::Slides::Warnings](../../)
* Könyvtár [Aspose.Slides](../../../)
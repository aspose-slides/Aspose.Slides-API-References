---
title: get_InterruptionToken()
second_title: Aspose.Slides C++ API referencia
description: Az token a megszakítási kérések figyelésére szolgál.
type: docs
weight: 235
url: /hu/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() metódus

Az token a megszakítási kérések figyelésére szolgál.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Megjegyzések

Ez a token kezeli a teljes [IPresentation](../../ipresentation/) példány élettartamát. Bármely hosszú futású művelet, például a prezentáció betöltése vagy mentése, a [IInterruptionTokenSource](../../iinterruptiontokensource/) [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) metódusának meghívásával lesz megszakítva.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IInterruptionToken](../../iinterruptiontoken/)
* Osztály [ILoadOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
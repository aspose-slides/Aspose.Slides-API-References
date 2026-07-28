---
title: set_InterruptionToken()
second_title: Aspose.Slides C++ API referencia
description: Az token a megszakítási kérések figyelésére szolgál.
type: docs
weight: 248
url: /hu/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metódus

Az token a megszakítási kérések figyelésére szolgál.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Megjegyzések

Ez a token kezeli a teljes [IPresentation](../../ipresentation/) példány életciklusát. Bármely hosszú futású művelet, például a prezentáció betöltése vagy mentése, a [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) metódus meghívásával lesz megszakítva a [IInterruptionTokenSource](../../iinterruptiontokensource/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IInterruptionToken](../../iinterruptiontoken/)
* Osztály [ILoadOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
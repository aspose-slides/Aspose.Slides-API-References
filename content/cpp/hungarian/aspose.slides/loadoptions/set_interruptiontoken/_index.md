---
title: set_InterruptionToken()
second_title: Aspose.Slides C++ API referencia
description: A token, amely a megszakítási kérések figyelésére szolgál.
type: docs
weight: 248
url: /hu/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metódus

A token, amely a megszakítási kérések figyelésére szolgál.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Megjegyzések

Ez a token kezeli a teljes [IPresentation](../../ipresentation/) példány életciklusát. Bármely hosszú ideig futó művelet, például a prezentáció betöltése vagy mentése, a [InterruptionTokenSource](../../interruptiontokensource/) [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) metódusának meghívásával lesz megszakítva.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IInterruptionToken](../../iinterruptiontoken/)
* Osztály [LoadOptions](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
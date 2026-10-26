---
title: get_InterruptionToken()
second_title: Aspose.Slides C++ API-referencia
description: Az a token, amely a megszakítási kérések figyelésére szolgál.
type: docs
weight: 235
url: /hu/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() method

A token, amely a megszakítási kérések figyelésére szolgál.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Megjegyzés

Ez a token kezeli a teljes [IPresentation](../../ipresentation/) példány élettartamát. Bármely hosszú ideig futó művelet, például a prezentáció betöltése vagy mentése, megszakításra kerül a [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) metódus meghívásával a [InterruptionTokenSource](../../interruptiontokensource/)-nél.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IInterruptionToken](../../iinterruptiontoken/)
* Osztály [LoadOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
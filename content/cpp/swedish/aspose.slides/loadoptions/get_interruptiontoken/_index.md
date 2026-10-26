---
title: get_InterruptionToken()
second_title: Aspose.Slides för C++ API-referens
description: Tokenet för att övervaka avbrottsförfrågningar.
type: docs
weight: 235
url: /sv/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() metod


Tokenet för att övervaka avbrottsförfrågningar.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Anmärkningar


Denna token hanterar hela [IPresentation](../../ipresentation/)-instansens livstid. Alla långvariga operationer, såsom inläsning eller sparande av presentation, avbryts genom att anropa [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) metod i [InterruptionTokenSource](../../interruptiontokensource/). 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IInterruptionToken](../../iinterruptiontoken/)
* Klass [LoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
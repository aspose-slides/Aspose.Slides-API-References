---
title: set_InterruptionToken()
second_title: Aspose.Slides för C++ API-referens
description: Tokenet för att övervaka avbrottsförfrågningar.
type: docs
weight: 248
url: /sv/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metod


Tokenet för att övervaka avbrottsförfrågningar.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Anmärkningar


Denna token hanterar hela [IPresentation](../../ipresentation/)-instansens livstid. Alla långvariga operationer, såsom inläsning eller sparande av presentation, avbryts genom att anropa [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/)-metoden i [InterruptionTokenSource](../../interruptiontokensource/). 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IInterruptionToken](../../iinterruptiontoken/)
* Klass [LoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
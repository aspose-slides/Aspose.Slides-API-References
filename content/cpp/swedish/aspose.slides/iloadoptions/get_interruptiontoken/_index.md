---
title: get_InterruptionToken()
second_title: Aspose.Slides för C++ API-referens
description: Tokenet för att övervaka avbrottsförfrågningar.
type: docs
weight: 235
url: /sv/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() metod


Tokenet för att övervaka avbrottsförfrågningar.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Anmärkningar


Detta token hanterar hela [IPresentation](../../ipresentation/)-instansens livslängd. Alla långvariga operationer, såsom inläsning eller sparande av presentation, avbryts genom att anropa [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/)-metoden i [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IInterruptionToken](../../iinterruptiontoken/)
* Klass [ILoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
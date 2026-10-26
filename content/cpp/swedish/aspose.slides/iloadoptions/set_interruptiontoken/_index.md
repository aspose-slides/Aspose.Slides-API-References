---
title: set_InterruptionToken()
second_title: Aspose.Slides för C++ API-referens
description: Token för att övervaka avbrottsförfrågningar.
type: docs
weight: 248
url: /sv/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metod


Token för att övervaka avbrottsbegäran.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Anmärkningar


Denna token hanterar hela [IPresentation](../../ipresentation/)-instansens livslängd. Alla långvariga operationer, såsom presentationens laddning eller sparning, kommer att avbrytas via anrop av [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/)-metoden i [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [ILoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
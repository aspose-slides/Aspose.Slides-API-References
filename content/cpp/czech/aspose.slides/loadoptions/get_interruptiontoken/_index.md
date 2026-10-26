---
title: get_InterruptionToken()
second_title: Aspose.Slides pro C++ API Reference
description: Token pro sledování žádostí o přerušení.
type: docs
weight: 235
url: /cs/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() metoda


Token pro sledování žádostí o přerušení.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Poznámky


Tento token spravuje celou životnost instance [IPresentation](../../ipresentation/). Jakákoli dlouho běžící operace, například načítání nebo ukládání prezentace, bude přerušena voláním metody [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) objektu [InterruptionTokenSource](../../interruptiontokensource/). 
## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IInterruptionToken](../../iinterruptiontoken/)
* Třída [LoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
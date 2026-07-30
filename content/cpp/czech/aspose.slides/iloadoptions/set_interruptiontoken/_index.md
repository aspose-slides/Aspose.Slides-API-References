---
title: set_InterruptionToken()
second_title: Aspose.Slides pro C++ API Reference
description: Token pro sledování požadavků na přerušení.
type: docs
weight: 248
url: /cs/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metoda

Token pro sledování požadavků na přerušení.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Poznámky

Tento token spravuje celou životnost instance [IPresentation](../../ipresentation/). Každá dlouho běžící operace, například načítání nebo ukládání prezentace, bude přerušena voláním [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) metoda [IInterruptionTokenSource](../../iinterruptiontokensource/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IInterruptionToken](../../iinterruptiontoken/)
* Třída [ILoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
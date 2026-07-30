---
title: set_InterruptionToken()
second_title: Aspose.Slides pro C++ – reference API
description: Token pro sledování požadavků na přerušení.
type: docs
weight: 248
url: /cs/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metoda

Token pro sledování požadavků na přerušení.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Poznámky

Tento token spravuje celou dobu života instance [IPresentation](../../ipresentation/). Jakákoli dlouho běžící operace, jako načítání nebo ukládání prezentace, bude přerušena zavoláním metody [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) třídy [InterruptionTokenSource](../../interruptiontokensource/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IInterruptionToken](../../iinterruptiontoken/)
* Třída [LoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
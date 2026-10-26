---
title: get_InterruptionToken()
second_title: Aspose.Slides pro C++ API Reference
description: Token pro sledování požadavků na přerušení.
type: docs
weight: 235
url: /cs/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() metoda


Token k monitorování požadavků na přerušení.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Poznámky


Tento token spravuje celou životnost instance [IPresentation](../../ipresentation/). Jakákoli dlouho běžící operace, jako je načítání nebo ukládání prezentace, bude přerušena voláním metody [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) třídy [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IInterruptionToken](../../iinterruptiontoken/)
* třída [ILoadOptions](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
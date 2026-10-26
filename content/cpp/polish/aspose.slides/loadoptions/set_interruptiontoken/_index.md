---
title: set_InterruptionToken()
second_title: Aspose.Slides dla C++ - Referencja API
description: Token służący do monitorowania żądań przerwania.
type: docs
weight: 248
url: /pl/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metoda

Token służący do monitorowania żądań przerwania.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Uwagi

Ten token zarządza całym okresem życia instancji [IPresentation](../../ipresentation/). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) obiektu [InterruptionTokenSource](../../interruptiontokensource/). 

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
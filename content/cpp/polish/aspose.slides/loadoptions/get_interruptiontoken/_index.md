---
title: get_InterruptionToken()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Token do monitorowania żądań przerwania.
type: docs
weight: 235
url: /pl/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() metoda

Token do monitorowania żądań przerwania.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Uwagi

Ten token zarządza całym okresem życia instancji [IPresentation](../../ipresentation/). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) obiektu [InterruptionTokenSource](../../interruptiontokensource/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IInterruptionToken](../../iinterruptiontoken/)
* Klasa [LoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
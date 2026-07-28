---
title: get_InterruptionToken()
second_title: Aspose.Slides dla C++ – referencja API
description: Token używany do monitorowania żądań przerwania.
type: docs
weight: 235
url: /pl/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() metoda

Token używany do monitorowania żądań przerwania.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Uwagi

Ten token zarządza całym okresem życia instancji [IPresentation](../../ipresentation/). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) obiektu [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IInterruptionToken](../../iinterruptiontoken/)
* Klasa [ILoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
---
title: set_InterruptionToken()
second_title: Odwołanie API Aspose.Slides dla C++
description: Token służący do monitorowania żądań przerwania.
type: docs
weight: 248
url: /pl/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metoda

Token służący do monitorowania żądań przerwania.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Uwagi

Ten token zarządza całym okresem życia instancji [IPresentation](../../ipresentation/). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) metody [IInterruptionTokenSource](../../iinterruptiontokensource/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IInterruptionToken](../../iinterruptiontoken/)
* Klasa [ILoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
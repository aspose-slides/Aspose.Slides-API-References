---
title: set_InterruptionToken()
second_title: Aspose.Slides für C++ API-Referenz
description: Das Token zur Überwachung von Unterbrechungsanfragen.
type: docs
weight: 248
url: /de/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) Methode

Das Token zur Überwachung von Unterbrechungsanfragen.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Anmerkungen

Dieses Token verwaltet die gesamte Lebensdauer der [IPresentation](../../ipresentation/)-Instanz. Jede langlaufende Operation, wie das Laden oder Speichern einer Präsentation, wird durch Aufrufen der [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/)-Methode des [IInterruptionTokenSource](../../iinterruptiontokensource/) unterbrochen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInterruptionToken](../../iinterruptiontoken/)
* Klasse [ILoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)
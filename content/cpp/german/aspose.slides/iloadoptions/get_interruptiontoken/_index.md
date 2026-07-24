---
title: get_InterruptionToken()
second_title: Aspose.Slides für C++ API-Referenz
description: Das Token zum Überwachen von Unterbrechungsanfragen.
type: docs
weight: 235
url: /de/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() Methode

Das Token zum Überwachen von Unterbrechungsanfragen.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Anmerkungen

Dieses Token verwaltet die gesamte Lebensdauer der [IPresentation](../../ipresentation/)-Instanz. Jeder langlaufende Vorgang, wie das Laden oder Speichern einer Präsentation, wird durch Aufruf der [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/)-Methode des [IInterruptionTokenSource](../../iinterruptiontokensource/) unterbrochen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInterruptionToken](../../iinterruptiontoken/)
* Klasse [ILoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)
---
title: get_InterruptionToken()
second_title: Aspose.Slides für C++ API-Referenz
description: Das Token zur Überwachung von Unterbrechungsanfragen.
type: docs
weight: 235
url: /de/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() Methode

Das Token zur Überwachung von Unterbrechungsanfragen.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Hinweise

Dieses Token verwaltet die gesamte Lebensdauer der [IPresentation](../../ipresentation/)-Instanz. Jede langlaufende Operation, wie das Laden oder Speichern einer Präsentation, wird durch Aufruf der [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/)-Methode des [InterruptionTokenSource](../../interruptiontokensource/) unterbrochen. 

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInterruptionToken](../../iinterruptiontoken/)
* Klasse [LoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)
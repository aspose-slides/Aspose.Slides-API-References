---
title: set_InterruptionToken()
second_title: Aspose.Slides für C++ API-Referenz
description: Das Token zur Überwachung von Unterbrechungsanfragen.
type: docs
weight: 248
url: /de/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) Methode


Das Token zur Überwachung von Unterbrechungsanfragen.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Hinweise


Dieses Token verwaltet die gesamte Lebensdauer der [IPresentation](../../ipresentation/)-Instanz. Jeder langlaufende Vorgang, wie das Laden oder Speichern einer Präsentation, wird durch den Aufruf der [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/)-Methode des [InterruptionTokenSource](../../interruptiontokensource/) unterbrochen. 
## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInterruptionToken](../../iinterruptiontoken/)
* Klasse [LoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)
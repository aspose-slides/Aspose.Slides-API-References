---
title: set_InterruptionToken()
second_title: Aspose.Slides voor C++ API-referentie
description: De token om te controleren op onderbrekingsverzoeken.
type: docs
weight: 248
url: /nl/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) methode

De token om te controleren op onderbrekingsverzoeken.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Opmerkingen

Deze token beheert de volledige [IPresentation](../../ipresentation/) instantielevensduur. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) methode van de [InterruptionTokenSource](../../interruptiontokensource/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInterruptionToken](../../iinterruptiontoken/)
* Klasse [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
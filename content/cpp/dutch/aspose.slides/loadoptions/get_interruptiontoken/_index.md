---
title: get_InterruptionToken()
second_title: Aspose.Slides voor C++ API-referentie
description: Het token om onderbrekingsverzoeken te monitoren.
type: docs
weight: 235
url: /nl/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() methode

Het token om onderbrekingsverzoeken te monitoren.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Opmerkingen

Dit token beheert de volledige levensduur van de [IPresentation](../../ipresentation/)-instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/)-methode van de [InterruptionTokenSource](../../interruptiontokensource/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInterruptionToken](../../iinterruptiontoken/)
* Klasse [LoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
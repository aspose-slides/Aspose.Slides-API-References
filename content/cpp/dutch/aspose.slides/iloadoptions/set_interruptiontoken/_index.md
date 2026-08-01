---
title: set_InterruptionToken()
second_title: Aspose.Slides voor C++ API-referentie
description: Het token om onderbrekingsverzoeken te monitoren.
type: docs
weight: 248
url: /nl/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) methode


Het token om onderbrekingsverzoeken te monitoren.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Opmerkingen


Dit token beheert de volledige levensduur van de [IPresentation](../../ipresentation/) instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, zal worden onderbroken door het aanroepen van de [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) methode van de [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInterruptionToken](../../iinterruptiontoken/)
* Klasse [ILoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
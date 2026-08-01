---
title: get_InterruptionToken()
second_title: Aspose.Slides voor C++ API-referentie
description: Het token om onderbrekingsverzoeken te bewaken.
type: docs
weight: 235
url: /nl/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() methode


Het token om onderbrekingsverzoeken te bewaken.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Opmerkingen


Dit token beheert de volledige levensduur van de [IPresentation](../../ipresentation/) instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, zal worden onderbroken door het aanroepen van de [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) methode van de [IInterruptionTokenSource](../../iinterruptiontokensource/). 
 ## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInterruptionToken](../../iinterruptiontoken/)
* Klasse [ILoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
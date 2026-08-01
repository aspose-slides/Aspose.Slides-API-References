---
title: UpdateDocumentProperties()
second_title: Aspose.Slides voor C++ API-referentie
description: Werkt de eigenschappen van de gekoppelde presentatie bij.
type: docs
weight: 92
url: /nl/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) method

Werk de eigenschappen van de gekoppelde presentatie bij.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Opmerkingen

Dit voorbeeld laat zien hoe de [PresentationInfo::UpdateDocumentProperties](./) methode kan worden aangeroepen om de documenteigenschappen bij te werken die worden geretourneerd door een aanroep van de [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) methode. 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDocumentProperties](../../idocumentproperties/)
* Klasse [PresentationInfo](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: UpdateDocumentProperties()
second_title: Aspose.Slides voor C++ API-referentie
description: Werk de eigenschappen van de gekoppelde presentatie bij.
type: docs
weight: 92
url: /nl/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) methode

Werkt de eigenschappen van de gekoppelde presentatie bij.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Document properties [IDocumentProperties](../../idocumentproperties/) |

## Opmerkingen

Dit voorbeeld laat zien hoe de [IPresentationInfo::UpdateDocumentProperties](./) methode aan te roepen om de documenteigenschappen bij te werken die worden geretourneerd door een aanroep van de [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) methode. 
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
* Klasse [IPresentationInfo](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
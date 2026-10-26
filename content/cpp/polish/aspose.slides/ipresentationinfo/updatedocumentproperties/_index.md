---
title: UpdateDocumentProperties()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Aktualizuje właściwości powiązanej prezentacji.
type: docs
weight: 92
url: /pl/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) method

Aktualizuje właściwości podłączonej prezentacji.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Właściwości dokumentu [IDocumentProperties](../../idocumentproperties/) |
## Uwagi

Ten przykład pokazuje, jak wywołać metodę [IPresentationInfo::UpdateDocumentProperties](./), aby zaktualizować właściwości dokumentu zwrócone przez wywołanie metody [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/).
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDocumentProperties](../../idocumentproperties/)
* Klasa [IPresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
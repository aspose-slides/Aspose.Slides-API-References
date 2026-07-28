---
title: UpdateDocumentProperties()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Aktualizuje właściwości powiązanej prezentacji.
type: docs
weight: 92
url: /pl/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metoda

Aktualizuje właściwości powiązanej prezentacji.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Uwagi

Ten przykład pokazuje, jak wywołać metodę [PresentationInfo::UpdateDocumentProperties](./), aby zaktualizować właściwości dokumentu zwrócone przez wywołanie metody [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/). 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDocumentProperties](../../idocumentproperties/)
* Klasa [PresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
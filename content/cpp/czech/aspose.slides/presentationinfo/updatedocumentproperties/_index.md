---
title: UpdateDocumentProperties()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Aktualizuje vlastnosti svázané prezentace.
type: docs
weight: 92
url: /cs/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metoda

Aktualizuje vlastnosti svázané prezentace.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Poznámky


Tento příklad ukazuje, jak zavolat metodu [PresentationInfo::UpdateDocumentProperties](./) k aktualizaci vlastností dokumentu vrácených voláním metody [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/).

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDocumentProperties](../../idocumentproperties/)
* Třída [PresentationInfo](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
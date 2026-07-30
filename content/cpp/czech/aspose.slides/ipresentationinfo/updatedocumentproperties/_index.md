---
title: UpdateDocumentProperties()
second_title: Aspose.Slides pro C++ API Reference
description: Aktualizuje vlastnosti svázané prezentace.
type: docs
weight: 92
url: /cs/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metoda

Aktualizuje vlastnosti svázané prezentace.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Vlastnosti dokumentu [IDocumentProperties](../../idocumentproperties/) |

## Poznámky

Tento příklad ukazuje, jak zavolat metodu [IPresentationInfo::UpdateDocumentProperties](./) pro aktualizaci vlastností dokumentu vrácených voláním metody [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/).

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
* Třída [IPresentationInfo](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
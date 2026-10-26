---
title: UpdateDocumentProperties()
second_title: Aspose.Slides C++ API Referencia
description: Frissíti a kötött prezentáció tulajdonságait.
type: docs
weight: 92
url: /hu/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metódus

Frissíti a kötött prezentáció tulajdonságait.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Dokumentum tulajdonságai [IDocumentProperties](../../idocumentproperties/) |

## Megjegyzések

Ez a példa bemutatja, hogyan hívható a [IPresentationInfo::UpdateDocumentProperties](./) metódus a dokumentum tulajdonságok frissítéséhez, amelyet a [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) metódus hívása ad vissza.
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IDocumentProperties](../../idocumentproperties/)
* Osztály [IPresentationInfo](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
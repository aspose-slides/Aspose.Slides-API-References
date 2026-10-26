---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API hivatkozás
description: Frissíti a kapcsolt prezentáció tulajdonságait.
type: docs
weight: 92
url: /hu/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metódus


Frissíti a csatolt prezentáció tulajdonságait.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Megjegyzések


Ez a példa bemutatja, hogyan hívhatja a [PresentationInfo::UpdateDocumentProperties](./) metódust a dokumentumtulajdonságok frissítéséhez, amelyet a [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) metódus hívása ad vissza. 
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
* Osztály [PresentationInfo](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
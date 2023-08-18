---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API Reference
description: Updates properties of binded presentation.
type: docs
weight: 92
url: /aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) method


Updates properties of binded presentation.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Remarks


This sample shows how to call the [PresentationInfo::UpdateDocumentProperties](./) method to update the document properties returned by call of the [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) method. 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDocumentProperties](../../idocumentproperties/)
* Class [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
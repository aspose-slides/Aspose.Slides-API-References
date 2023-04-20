---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API Reference
description: Updates properties of binded presentation.
type: docs
weight: 92
url: /cpp/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) method


Updates properties of binded presentation.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Document properties [IDocumentProperties](../../idocumentproperties/) |
## Remarks



This sample shows how to call the [IPresentationInfo::UpdateDocumentProperties](./) method to update the document properties returned by call of the [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) method. 
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
* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
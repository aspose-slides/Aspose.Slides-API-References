---
title: UpdateDocumentProperties()
second_title: Aspose.Slides för C++ API-referens
description: Uppdaterar egenskaperna för den bundna presentationen.
type: docs
weight: 92
url: /sv/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metod


Uppdaterar egenskaperna för den bundna presentationen.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Dokumentegenskaper [IDocumentProperties](../../idocumentproperties/) |
## Remarks



Detta exempel visar hur man anropar [IPresentationInfo::UpdateDocumentProperties](./)-metoden för att uppdatera dokumentegenskaperna som returneras av anropet av [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/)-metoden. 
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
* Klass [IDocumentProperties](../../idocumentproperties/)
* Klass [IPresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
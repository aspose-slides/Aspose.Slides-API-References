---
title: UpdateDocumentProperties()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بتحديث خصائص العرض المرتبط.
type: docs
weight: 92
url: /ar/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) طريقة


يقوم بتحديث خصائص العرض المرتبط.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | خصائص المستند [IDocumentProperties](../../idocumentproperties/) |
## ملاحظات



يعرض هذا المثال كيفية استدعاء [IPresentationInfo::UpdateDocumentProperties](./) الطريقة لتحديث خصائص المستند التي تم إرجاعها عند استدعاء [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) الطريقة. 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDocumentProperties](../../idocumentproperties/)
* فئة [IPresentationInfo](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
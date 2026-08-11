---
title: UpdateDocumentProperties()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحديث خصائص العرض المرتبط.
type: docs
weight: 92
url: /ar/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) طريقة


يقوم بتحديث خصائص العرض المرتبط.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## ملاحظات


يوضح هذا المثال كيفية استدعاء طريقة [PresentationInfo::UpdateDocumentProperties](./) لتحديث خصائص المستند التي تم إرجاعها بواسطة استدعاء طريقة [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/).
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IDocumentProperties](../../idocumentproperties/)
* الفئة [PresentationInfo](../)
* النطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
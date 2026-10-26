---
title: UpdateDocumentProperties()
second_title: Aspose.Slides برای مرجع API C++
description: ویژگی‌های ارائهٔ پیوست شده را به‌روزرسانی می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) متد


ویژگی‌های ارائهٔ پیوست شده را به‌روزرسانی می‌کند.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## ملاحظات


این نمونه نشان می‌دهد چگونه می‌توان متد [PresentationInfo::UpdateDocumentProperties](./) را برای به‌روزرسانی ویژگی‌های سندی که توسط فراخوانی متد [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) بازگردانده می‌شود، فراخوانی کرد. 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDocumentProperties](../../idocumentproperties/)
* Class [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
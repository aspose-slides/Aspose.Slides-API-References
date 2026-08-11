---
title: UpdateDocumentProperties()
second_title: مرجع API Aspose.Slides برای C++
description: ویژگی‌های ارائهٔ متصل را به‌روزرسانی می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) روش

مشخصات ارائهٔ مرتبط را به‌روزرسانی می‌کند.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | ویژگی‌های سند [IDocumentProperties](../../idocumentproperties/) |

## ملاحظات

این نمونه نشان می‌دهد چگونه می‌توان متد [IPresentationInfo::UpdateDocumentProperties](./) را برای به‌روزرسانی ویژگی‌های سند که توسط فراخوانی متد [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) بازگردانده می‌شود، صدا زد.
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## همچنین ببینید

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDocumentProperties](../../idocumentproperties/)
* کلاس [IPresentationInfo](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
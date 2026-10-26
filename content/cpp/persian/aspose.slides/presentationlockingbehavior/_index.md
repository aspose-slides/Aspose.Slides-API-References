---
title: PresentationLockingBehavior
second_title: مرجع API Aspose.Slides برای C++
description: "رفتار مربوط به نحوهٔ برخورد با منبع IPresentation (فایل یا System::IO::Stream) هنگام بارگذاری و کار با یک نمونه از IPresentation را نشان می‌دهد."
type: docs
weight: 6748
url: /fa/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum


رفتار مرتبط با نحوهٔ برخورد با منبع [IPresentation](../ipresentation/) (فایل یا [System::IO::Stream](../../system.io/stream/)) هنگام بارگذاری و کار با یک نمونه از [IPresentation](../ipresentation/) را نشان می‌دهد.

```cpp
enum class PresentationLockingBehavior
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| LoadAndRelease | 0 | منبع فقط برای مدت اجرای سازنده [IPresentation](../ipresentation/) قفل خواهد شد. |
| KeepLocked | 1 | منبع برای تمام طول عمر نمونه [IPresentation](../ipresentation/) قفل خواهد شد، تا زمانی که نابود شود. |

## ملاحظات


منبع پارامتری است که به سازنده [IPresentation](../ipresentation/) ارسال می‌شود. در مثال زیر، منبع فایل "pres.pptx" است: 

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

در این مثال، منبع (فایل "pres.pptx") برای طول عمر نمونه [IPresentation](../ipresentation/) قفل خواهد شد، یعنی توسط پردازش دیگر نمی‌تواند تغییر یا حذف شود. 
## موارد مرتبط

* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)
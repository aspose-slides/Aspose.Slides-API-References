---
title: PresentationLockingBehavior
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل السلوك المتعلق بمعالجة مصدر IPresentation (ملف أو System::IO::Stream) أثناء التحميل والعمل مع نسخة من IPresentation."
type: docs
weight: 6748
url: /ar/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

يمثل السلوك المتعلق بمعالجة المصدر [IPresentation](../ipresentation/) (ملف أو [System::IO::Stream](../../system.io/stream/)) أثناء التحميل والعمل مع نسخة من [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| LoadAndRelease | 0 | سيتم قفل المصدر فقط لفترة تنفيذ منشئ [IPresentation](../ipresentation/). |
| KeepLocked | 1 | سيتم قفل المصدر طوال عمر نسخة [IPresentation](../ipresentation/)، حتى يتم التخلص منها. |

## ملاحظات

المصدر هو المعامل المرسل إلى منشئ [IPresentation](../ipresentation/). في المثال أدناه، المصدر هو الملف "pres.pptx": 

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

في هذا المثال، سيتم قفل المصدر (ملف "pres.pptx") طوال عمر نسخة [IPresentation](../ipresentation/)، أي لا يمكن تغييره أو حذفه بواسطة العملية الأخرى. 
## انظر أيضًا

* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)
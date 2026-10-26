---
title: get_PresentationLockingBehavior()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تحدد هذه الخاصية ما إذا كان كائن من الفئة Presentation يمكن أن يكون مالكًا للمصدر - ملف أو تدفق خلال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد هذا على تحسين استهلاك الذاكرة والأداء أثناء العمل مع الـ BLOBs، لكن لا يمكن تغيير المصدر (تدفق أو ملف) خلال عمر كائن Presentation. هذا مثال:"
type: docs
weight: 1
url: /ar/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() طريقة

هذه الخاصية تحدد ما إذا كان كائن من الفئة [Presentation](../../presentation/) يمكن أن يكون مالكًا للمصدر - ملف أو تدفق خلال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. هذا يساعد على تحسين استهلاك الذاكرة والأداء أثناء العمل مع الـ BLOBs، لكن لا يمكن تغيير المصدر (تدفق أو ملف) خلال عمر الكائن [Presentation](../../presentation/). هذا مثال:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## ملاحظات

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // سيتم إلقاء IOException لأن ملف pres.pptx مقفل طوال عمر الـ Presentation
    // File::Delete(u"pres.pptx");
}
// بعد تدمير كائن Presentation، يتم فك قفل الملف ويمكن حذفه
IO::File::Delete(u"pres.pptx");
```

## انظر أيضا

* تعداد [PresentationLockingBehavior](../../presentationlockingbehavior/)
* فئة [IBlobManagementOptions](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
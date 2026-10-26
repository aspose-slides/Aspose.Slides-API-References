---
title: set_PresentationLockingBehavior()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "هذه الخاصية تحدد ما إذا كان كائن من الفئة Presentation يمكنه أن يكون مالكًا للمصدر - ملف أو تدفق طوال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك على تحسين استهلاك الذاكرة والأداء عند العمل مع BLOBs، لكن لا يمكن تغيير المصدر (التدفق أو الملف) خلال عمر مثيل Presentation. هذا مثال:"
type: docs
weight: 14
url: /ar/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) طريقة

تحدد هذه الخاصية ما إذا كان كائن من الفئة [Presentation](../../presentation/) يمكنه أن يكون مالكًا للمصدر - ملف أو تدفق طوال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك في تحسين استهلاك الذاكرة والأداء عند العمل مع الـBLOBs، لكن لا يمكن تغيير المصدر (تدفق أو ملف) خلال عمر المثيل الخاص بـ[Presentation](../../presentation/). هذا مثال:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## ملاحظات

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // سيتم إلقاء IOException لأن ملف pres.pptx مقفل طوال مدة كائن Presentation
    // File::Delete(u"pres.pptx");
}
// بعد تدمير كائن Presentation، يتم فك قفل الملف ويمكن حذفه
IO::File::Delete(u"pres.pptx");
```

## انظر أيضًا

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
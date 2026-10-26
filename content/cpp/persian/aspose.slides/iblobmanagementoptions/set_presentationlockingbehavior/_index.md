---
title: set_PresentationLockingBehavior()
second_title: مستندات API Aspose.Slides برای C++
description: "این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان در طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این کار به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) را نمی‌توان در طول عمر نمونه Presentation تغییر داد. این یک مثال است:"
type: docs
weight: 14
url: /fa/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) متد

این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس [Presentation](../../presentation/) می‌تواند مالک منبع - فایل یا جریان در مدت زمان عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این کار به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) را نمی‌توان در طول عمر نمونه [Presentation](../../presentation/)'s تغییر داد. این یک مثال است:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## توضیحات


```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // استثنای IOException پرتاب می‌شود چون فایل pres.pptx برای طول عمر Presentation قفل شده است
    // File::Delete(u"pres.pptx");
}
// پس از از بین رفتن شیء Presentation، فایل باز می‌شود و می‌توان آن را حذف کرد
IO::File::Delete(u"pres.pptx");
```

## موارد مرتبط

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* کلاس [IBlobManagementOptions](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
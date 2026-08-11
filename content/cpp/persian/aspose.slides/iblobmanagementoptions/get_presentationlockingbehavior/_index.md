---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides برای C++ راهنمای API
description: "این ویژگی تعیین می‌کند که آیا یک نمونه از کلاس Presentation می‌تواند مالک منبع - فایل یا جریان در طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) در طول عمر نمونه Presentation نمی‌تواند تغییر کند. این یک مثال است:"
type: docs
weight: 1
url: /fa/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() متد

این ویژگی مشخص می‌کند که آیا یک نمونه از کلاس [Presentation](../../presentation/) می‌تواند مالک منبع - فایل یا جریان در طول عمر نمونه باشد. اگر نمونه مالک باشد، منبع را قفل می‌کند. این به بهبود مصرف حافظه و عملکرد هنگام کار با BLOBها کمک می‌کند، اما منبع (جریان یا فایل) در طول عمر نمونه [Presentation](../../presentation/) نمی‌تواند تغییر کند. این یک مثال است:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## توضیحات

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // به دلیل قفل بودن pres.pptx برای طول عمر یک Presentation، IOException صادر خواهد شد
    // File::Delete(u"pres.pptx");
}
// پس از نابود شدن شیء Presentation، فایل باز می‌شود و می‌تواند حذف شود
IO::File::Delete(u"pres.pptx");
```

## موارد مرتبط

* enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* کلاس [IBlobManagementOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
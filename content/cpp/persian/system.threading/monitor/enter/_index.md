---
title: Enter()
second_title: Aspose.Slides برای C++ مرجع API
description: قفل انحصاری را بر روی شیء مشخص‌شده می‌گیرد.
type: docs
weight: 1
url: /fa/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) متد

قفل اختصاصی را بر روی شیء مشخص‌شده به‌دست می‌آورد.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | شیئی که می‌خواهید قفل مانیتور را بر روی آن بگیرید. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) متد

قفل اختصاصی را بر روی شیء مشخص‌شده به‌دست می‌آورد و به‌صورت اتمی مقدار نشان‌دهنده‌ی این‌که آیا قفل گرفته شده است را تنظیم می‌کند.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [Monitor](../)
* فضای‌نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)
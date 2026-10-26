---
title: WeakReference<>
second_title: مرجع API Aspose.Slides برای C++
description: یک ارجاع ضعیف را نشان می‌دهد که به یک شیء ارجاع می‌کند و در عین حال اجازه می‌دهد آن شیء حذف شود.
type: docs
weight: 1522
url: /fa/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> کلاس

یک ارجاع ضعیف را نشان می‌دهد که به یک شیء ارجاع می‌دهد و در عین حال اجازه می‌دهد آن شیء حذف شود.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | نشان می‌دهد که آیا شیء مرجع توسط شیء WeakReference جاری حذف شده است یا خیر. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | شیء (هدف) مرجع شده توسط شیء WeakReference جاری را بر می‌گرداند. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | شیء (هدف) مرجع شده توسط شیء WeakReference جاری را تنظیم می‌کند. |
|  [WeakReference](./weakreference/)() | سازنده پیش‌فرض. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | سازنده از nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | یک نمونه جدید از کلاس WeakReference را مقداردهی اولیه می‌کند که شیء مشخص‌شده را مرجع می‌گیرد. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | یک نمونه جدید از کلاس WeakReference را مقداردهی اولیه می‌کند که شیء مشخص‌شده را مرجع می‌گیرد. |

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)
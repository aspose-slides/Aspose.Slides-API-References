---
title: EnumValuesBase
second_title: مرجع API Aspose.Slides برای C++
description: کلاس پایه‌ای برای کلاسی که اطلاعات متادیتای نوع شمارش را نشان می‌دهد.
type: docs
weight: 807
url: /fa/system/enumvaluesbase/
---
## کلاس EnumValuesBase


یک کلاس پایه برای کلاسی که اطلاعات متادیتای نوع شمارش را نشان می‌دهد.

```cpp
class EnumValuesBase
```

## متدها

| متد | توضیح |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | یک آرایه از نام‌های ثابت‌های موجود در یک شمارش مشخص برمی‌گرداند. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | نوع زیربنایی شمارش مشخص شده را بر می‌گرداند. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | یک آرایه شامل تمام مقادیر نوع شمارش مشخص شده را برمی‌گرداند. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | یک شیء را برمی‌گرداند که نمایانگر مقداری از ثابت شمارش نوع شمارش مشخص شده با نام مشخص‌شده است. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | مقدار عدد صحیح بدون علامت 64-بیتی مشخص‌شده را به یک عضو شمارش تبدیل می‌کند. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | شیء مشخص‌شده با یک مقدار عدد صحیح را به یک عضو شمارش تبدیل می‌کند. |
## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)
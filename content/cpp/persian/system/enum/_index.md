---
title: Enum
second_title: Aspose.Slides برای C++ مرجع API
description: روش‌هایی را فراهم می‌کند که برخی عملیات را بر روی مقادیر نوع enum انجام می‌دهند. این یک نوع ایستاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وجه نمونه‌های آن را ایجاد کنید.
type: docs
weight: 1587
url: /fa/system/enum/
---
## ساختار Enum

روش‌هایی را فراهم می‌کند که برخی عملیات را بر روی مقادیر نوع enum انجام می‌دهند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید با هیچ راهی نمونه‌های آن را ایجاد کنید.

```cpp
template<class E,class Guard>class Enum
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| E | نوع enum که کلاس مقادیر آن را مدیریت می‌کند |
| Guard | آرگومان نوع سرویس که هدف آن اطمینان از این است که **E** یک نوع شمارشی است |

## متدها

| متد | توضیح |
| --- | --- |
| static int [Compare](./compare/)(E, T) | مقایسهٔ ریاضی مقادیر ثابت‌های شمارشی مشخص‌شده را انجام می‌دهد. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | نام ثابت شمارشی که مقدار مشخص‌شده را دارد برمی‌گرداند. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | نام ثابت شمارشی که مقدار مشخص‌شده را دارد برمی‌گرداند. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | یک آرایه شامل نام تمام اعضای شمارشی **E** برمی‌گرداند. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | نوع پایهٔ شمارش را برمی‌گرداند. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | یک آرایه شامل تمام اعضای شمارشی **E** برمی‌گرداند. |
| static **bool** [HasFlag](./hasflag/)(E, E) | تعیین می‌کند آیا بیت‌های مشخص‌شده در نمایش بیتی مقدار enum مشخص شده تنظیم شده‌اند. |
| static **bool** [IsDefined](./isdefined/)(E) | تعیین می‌کند آیا مقدار مشخص‌شده عضو نوع شمارشی **E** است. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | تعیین می‌کند آیا مقدار مشخص‌شده عضو نوع شمارشی **T** است. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | تعیین می‌کند آیا مقدار با نام مشخص‌شده جزو اعضای enum **E** است. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | رشتهٔ مشخص‌شده را به ثابت شمارشی معادل تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | سعی می‌کند رشتهٔ مشخص‌شده را به ثابت شمارشی معادل تبدیل کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | سعی می‌کند رشتهٔ مشخص‌شده را به ثابت شمارشی معادل تبدیل کند. |

## تعریف‌های نوع

| تعریف نوع | توضیح |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | نام دیگری برای نوع پایهٔ enum. |

## مراجعه کنید

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)
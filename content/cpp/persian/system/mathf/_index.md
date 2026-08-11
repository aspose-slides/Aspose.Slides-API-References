---
title: MathF
second_title: Aspose.Slides برای مرجع API زبان C++
description: حاوی توابع ریاضی برای مقادیر شناور با دقت تک-دقت است. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ‌وجه نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 1795
url: /fa/system/mathf/
---
## ساختار MathF

حاوی توابع ریاضی برای مقادیر ممیز شناور با دقت تک‌دقت (single-precision) است. این یک نوع استاتیک بدون سرویس‌های نمونه‌سازی است. شما هرگز نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.

```cpp
class MathF
```

## متدها

| متد | توضیح |
| --- | --- |
| static T [Abs](./abs/)(T) | مقدار مطلق مقدار مشخص شده را برمی‌گرداند. |
| static **float** [Acos](./acos/)(**float**) | آرک‌کسین مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Asin](./asin/)(**float**) | آرک‌سین مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Atan](./atan/)(**float**) | آرک‌تانژانت مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | آرک‌تانژانت نسبت مقادیر مشخص شده را محاسبه می‌کند. |
| static **float** [Ceiling](./ceiling/)(**float**) | کوچک‌ترین مقدار صحیح که بزرگ‌تر یا مساوی مقدار مشخص شده است را برمی‌گرداند. |
| static **float** [Cos](./cos/)(**float**) | کسینوس مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Cosh](./cosh/)(**float**) | کسینوس هیپربولیک مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Exp](./exp/)(**float**) | ثابت e را به توان مقدار مشخص شده برمی‌گرداند. |
| static **float** [Floor](./floor/)(**float**) | بزرگ‌ترین مقدار صحیح که کوچکتر یا مساوی مقدار مشخص شده است را برمی‌گرداند. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | باقی‌مانده حاصل‌تقسیم عدد مشخص شده بر عدد دیگری مشخص شده را برمی‌گرداند. |
| static **float** [Log](./log/)(**float**) | لگاریتم طبیعی مقدار مشخص شده را برمی‌گرداند. |
| static **float** [Log](./log/)(**float**, **float**) | لگاریتم مقدار مشخص شده در پایه مشخص شده را برمی‌گرداند. |
| static **float** [Log10](./log10/)(**float**) | لگاریتم پایه ۱۰ مقدار مشخص شده را برمی‌گرداند. |
| static **float** [Pow](./pow/)(**float**, **float**) | مقدار مشخص شده را به توان مقدار مشخص شده دیگر برمی‌گرداند. |
| static **float** [Round](./round/)(**float**) | مقدار مشخص شده را به نزدیک‌ترین مقدار صحیح گرد می‌کند. |
| static **float** [Round](./round/)(**float**, int) | مقدار مشخص شده را به نزدیک‌ترین مقدار با تعداد رقم کسری مشخص شده گرد می‌کند. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | مقدار مشخص شده را به نزدیک‌ترین عدد صحیح گرد می‌کند. پارامتری رفتار تابع را زمانی که مقدار مشخص شده به طور مساوی به دو عدد نزدیک‌ترین فاصله دارد، مشخص می‌کند. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | مقدار مشخص شده را به نزدیک‌ترین مقدار با تعداد رقم کسری مشخص شده گرد می‌کند. پارامتری رفتار تابع را زمانی که مقدار مشخص شده به طور مساوی به دو عدد نزدیک‌ترین فاصله دارد، مشخص می‌کند. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | مقدار مشخص شده را به نزدیک‌ترین مقدار با تعداد رقم کسری مشخص شده گرد می‌کند. پارامتری رفتار تابع را زمانی که مقدار مشخص شده به طور مساوی به دو عدد نزدیک‌ترین فاصله دارد، مشخص می‌کند. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | علامت مقدار صحیح علامت‌دار مشخص شده را تعیین می‌کند. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | علامت مقدار شناور (floating-point) مشخص شده را تعیین می‌کند. |
| static **float** [Sin](./sin/)(**float**) | سینوس مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Sinh](./sinh/)(**float**) | سینوس هیپربولیک مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Sqrt](./sqrt/)(**float**) | ریشهٔ مربعی مقدار مشخص شده را برمی‌گرداند. |
| static **float** [Tan](./tan/)(**float**) | تانژانت مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Tanh](./tanh/)(**float**) | تانژانت هیپربولیک مقدار مشخص شده را محاسبه می‌کند. |
| static **float** [Truncate](./truncate/)(**float**) | یک مقدار float-precision floating point value که بخش صحیح آن برابر با مقدار مشخص شده است و تمام ارقام کسری حذف شده‌اند، برمی‌گرداند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [E](./e/) | پایه لگاریتم طبیعی. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | ثابت عدد پی. |
| static [Tau](./tau/) | مقدار تاو. |

## مراجع

* نام‌فضا [System](../)
* کتابخانه [Aspose.Slides](../../)
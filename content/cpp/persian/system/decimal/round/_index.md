---
title: Round()
second_title: Aspose.Slides برای مرجع API C++
description: مقدار مشخص شده را به نزدیک‌ترین عدد صحیح گرد می‌کند. یک پارامتر رفتار تابع را زمانی که مقدار مشخص شده به‌طور مساوی به دو عدد نزدیک‌ترین نزدیک باشد، تعیین می‌کند.
type: docs
weight: 404
url: /fa/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) متد

عدد مشخص شده را به نزدیک‌ترین عدد صحیح گرد می‌کند. یک پارامتر رفتار تابع را زمانی که مقدار مشخص شده به‌طور مساوی به دو عدد نزدیک‌ترین نزدیک باشد، تعیین می‌کند.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | مقداری که باید گرد شود |
| mode | [MidpointRounding](../../midpointrounding/) | مشخص می‌کند که گرد کردن چگونه انجام شود اگر **value** به‌صورت مساوی به دو عدد نزدیک‌ترین نزدیک باشد. |

### مقدار بازگشتی

**d** به نزدیک‌ترین مقدار صحیح گرد شده

## Decimal::Round(const Decimal\&, int, MidpointRounding) متد

عدد مشخص شده را به نزدیک‌ترین مقدار با تعداد رقم‌های اعشاری مشخص شده گرد می‌کند. یک پارامتر رفتار تابع را زمانی که مقدار مشخص شده به‌طور مساوی به دو عدد نزدیک‌ترین نزدیک باشد، تعیین می‌کند.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | مقداری که باید گرد شود |
| digits | int | تعداد ارقام اعشار در مقدار گرد شده |
| mode | [MidpointRounding](../../midpointrounding/) | مشخص می‌کند که گرد کردن چگونه انجام شود اگر **value** به‌صورت مساوی به دو عدد نزدیک‌ترین نزدیک باشد. |

### مقدار بازگشتی

عدد با تعداد ارقام مشخص شده که به **value** نزدیک‌ترین است

## موارد مرتبط

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
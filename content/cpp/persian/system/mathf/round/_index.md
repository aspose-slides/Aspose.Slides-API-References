---
title: Round()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار مشخص شده را به نزدیک‌ترین مقدار صحیح گرد می‌کند.
type: docs
weight: 157
url: /fa/system/mathf/round/
---
## MathF::Round(float) متد

مقدار مشخص شده را به نزدیک‌ترین مقدار صحیح گرد می‌کند.

```cpp
static float System::MathF::Round(float a)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | **float** | مقدار برای گرد کردن |

### مقدار بازگشتی

**a** گرد‌شده به نزدیک‌ترین مقدار صحیح

## MathF::Round(float, int) متد

مقدار مشخص شده را به نزدیک‌ترین مقدار با تعداد رقم‌های اعشاری مشخص گرد می‌کند.

```cpp
static float System::MathF::Round(float value, int digits)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **float** | مقدار برای گرد کردن |
| digits | int | تعداد رقم‌های اعشاری در مقدار گرد شده |

### مقدار بازگشتی

عدد با تعداد رقم‌های مشخص که به **value** نزدیک‌ترین است

## MathF::Round(float, MidpointRounding) متد

مقدار مشخص شده را به نزدیک‌ترین عدد صحیح گرد می‌کند. پارامتر تعیین می‌کند که تابع چگونه رفتار کند اگر مقدار مشخص شده به اندازهٔ یکسان به دو عدد نزدیک‌ترین فاصله داشته باشد.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **float** | مقدار برای گرد کردن |
| mode | [MidpointRounding](../../midpointrounding/) | مشخص می‌کند که گرد کردن چگونه انجام شود اگر **value** به اندازهٔ یکسان به دو عدد نزدیک‌ترین فاصله داشته باشد. |

### مقدار بازگشتی

**value** گرد‌شده به نزدیک‌ترین مقدار صحیح

## MathF::Round(float, int, MidpointRounding) متد

مقدار مشخص شده را به نزدیک‌ترین مقدار با تعداد رقم‌های اعشاری مشخص گرد می‌کند. پارامتر تعیین می‌کند که تابع چگونه رفتار کند اگر مقدار مشخص شده به اندازهٔ یکسان به دو عدد نزدیک‌ترین فاصله داشته باشد.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **float** | مقدار برای گرد کردن |
| digits | int | تعداد رقم‌های اعشاری در مقدار گرد شده |
| mode | [MidpointRounding](../../midpointrounding/) | مشخص می‌کند که گرد کردن چگونه انجام شود اگر **value** به اندازهٔ یکسان به دو عدد نزدیک‌ترین فاصله داشته باشد. |

### مقدار بازگشتی

عدد با تعداد رقم‌های مشخص که به **value** نزدیک‌ترین است

## موارد مرتبط

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
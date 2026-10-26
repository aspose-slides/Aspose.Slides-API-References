---
title: Round()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار مشخص شده را به نزدیک‌ترین مقدار عدد صحیح گرد می‌کند.
type: docs
weight: 157
url: /fa/system/math/round/
---
## Math::Round(double) متد

مقدار مشخص شده را به نزدیک‌ترین مقدار عدد صحیح گرد می‌کند.

```cpp
static double System::Math::Round(double a)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | **double** | مقدار برای گرد کردن |

### مقدار بازگشت

**a** به نزدیک‌ترین مقدار عدد صحیح گرد شد

## Math::Round(double, int) متد

مقدار مشخص شده را به نزدیک‌ترین مقداری که تعداد رقم‌های کسری مشخص دارد، گرد می‌کند.

```cpp
static double System::Math::Round(double value, int digits)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **double** | مقدار برای گرد کردن |
| digits | int | تعداد ارقام کسری در مقدار گرد شده |

### مقدار بازگشت

عدد با تعداد ارقام مشخص که به **value** نزدیک‌ترین است

## Math::Round(double, MidpointRounding) متد

مقدار مشخص شده را به نزدیک‌ترین عدد صحیح گرد می‌کند. یک پارامتر رفتار تابع را مشخص می‌کند اگر مقدار مشخص شده به طور مساوی به دو عدد نزدیک‌ترین فاصله داشته باشد.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **double** | مقدار برای گرد کردن |
| mode | [MidpointRounding](../../midpointrounding/) | مشخص می‌کند چگونه گرد کردن انجام شود اگر **value** به طور مساوی به دو عدد نزدیک‌ترین فاصله داشته باشد. |

### مقدار بازگشت

**value** به نزدیک‌ترین مقدار عدد صحیح گرد شد

## Math::Round(double, int, MidpointRounding) متد

مقدار مشخص شده را به نزدیک‌ترین مقداری که تعداد رقم‌های کسری مشخص دارد، گرد می‌کند. یک پارامتر رفتار تابع را مشخص می‌کند اگر مقدار مشخص شده به طور مساوی به دو عدد نزدیک‌ترین فاصله داشته باشد.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **double** | مقدار برای گرد کردن |
| digits | int | تعداد ارقام کسری در مقدار گرد شده |
| mode | [MidpointRounding](../../midpointrounding/) | مشخص می‌کند چگونه گرد کردن انجام شود اگر **value** به طور مساوی به دو عدد نزدیک‌ترین فاصله داشته باشد. |

### مقدار بازگشت

عدد با تعداد ارقام مشخص که به **value** نزدیک‌ترین است

## Math::Round(const Decimal\&) متد

مقدار مشخص شده را به نزدیک‌ترین مقدار عدد صحیح گرد می‌کند.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | مقدار برای گرد کردن |

### مقدار بازگشت

**d** به نزدیک‌ترین مقدار عدد صحیح گرد شد

## Math::Round(const Decimal\&, int) متد

مقدار مشخص شده را به نزدیک‌ترین مقداری که تعداد رقم‌های کسری مشخص دارد، گرد می‌کند.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | مقدار برای گرد کردن |
| digits | int | تعداد ارقام کسری در مقدار گرد شده |

### مقدار بازگشت

عدد با تعداد ارقام مشخص که به **value** نزدیک‌ترین است

## Math::Round(const Decimal\&, MidpointRounding) متد

مقدار مشخص شده را به نزدیک‌ترین عدد صحیح گرد می‌کند. یک پارامتر رفتار تابع را مشخص می‌کند اگر مقدار مشخص شده به طور مساوی به دو عدد نزدیک‌ترین فاصله داشته باشد.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | مقدار برای گرد کردن |
| mode | [MidpointRounding](../../midpointrounding/) | مشخص می‌کند چگونه گرد کردن انجام شود اگر **value** به طور مساوی به دو عدد نزدیک‌ترین فاصله داشته باشد. |

### مقدار بازگشت

**d** به نزدیک‌ترین مقدار عدد صحیح گرد شد

## Math::Round(const Decimal\&, int, MidpointRounding) متد

مقدار مشخص شده را به نزدیک‌ترین مقداری که تعداد رقم‌های کسری مشخص دارد، گرد می‌کند. یک پارامتر رفتار تابع را مشخص می‌کند اگر مقدار مشخص شده به طور مساوی به دو عدد نزدیک‌ترین فاصله داشته باشد.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | مقدار برای گرد کردن |
| digits | int | تعداد ارقام کسری در مقدار گرد شده |
| mode | [MidpointRounding](../../midpointrounding/) | مشخص می‌کند چگونه گرد کردن انجام شود اگر **value** به طور مساوی به دو عدد نزدیک‌ترین فاصله داشته باشد. |

### مقدار بازگشت

عدد با تعداد ارقام مشخص که به **value** نزدیک‌ترین است

## موارد مرتبط

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
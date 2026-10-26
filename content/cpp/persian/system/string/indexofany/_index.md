---
title: IndexOfAny()
second_title: مرجع API Aspose.Slides برای C++
description: جستجوی پیش‌رو کاراکتر.
type: docs
weight: 638
url: /fa/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const متد

جستجوی پیش‌رو کاراکتر.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| c | char_t | کاراکتری که باید جستجو شود. |
| startIndex | int | [Index](../../index/) برای شروع جستجو. |

### مقدار بازگشتی

[Index](../../index/) از موقعیت اولین کاراکتر از startIndex یا -1 اگر یافت نشود.

## String::IndexOfAny(const String\&, int) const متد

به‌طور مقتضی به‌دنبال تمام کاراکترهای str در این رشته می‌گردد. اگر اولین کاراکتر یافت شود موقعیت آن برگردانده می‌شود، در غیر این صورت کاراکتر دوم جستجو می‌شود و به همین ترتیب.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) کاراکترها برای جستجو. ترتیب کاراکترها مهم است. |
| startIndex | int | موقعیتی برای شروع جستجو. |

### مقدار بازگشتی

[Index](../../index/) از اولین کاراکتر یافت‌شده یا -1 اگر هیچ‌کدام پیدا نشود.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const متد

به‌دنبال هر یک از کاراکترهای پاس‌داده‌شده در سراسر رشته می‌گردد. کاراکتر اول رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس کاراکتر دوم و به همین ترتیب. اندیس اولین کاراکتری که با هر یک از کاراکترهای هدف مطابقت دارد را برمی‌گرداند.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) کاراکترها برای جستجو. ترتیب مهم نیست. |

### مقدار بازگشتی

[Index](../../index/) از اولین کاراکتر مطابق یا -1 اگر یافت نشود.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const متد

به‌دنبال هر یک از کاراکترهای پاس‌داده‌شده در زیررشته می‌گردد. کاراکتر اول رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس کاراکتر دوم و به همین ترتیب. اندیس اولین کاراکتری که با هر یک از کاراکترهای هدف مطابقت دارد را برمی‌گرداند.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) کاراکترها برای جستجو. ترتیب مهم نیست. |
| startindex | **int32_t** | [Index](../../index/) برای شروع جستجو. |

### مقدار بازگشتی

[Index](../../index/) از اولین کاراکتر مطابق یا -1 اگر یافت نشود.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const متد

به‌دنبال هر یک از کاراکترهای پاس‌داده‌شده در زیررشته می‌گردد. کاراکتر اول رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس کاراکتر دوم و به همین ترتیب. اندیس اولین کاراکتری که با هر یک از کاراکترهای هدف مطابقت دارد را برمی‌گرداند.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) کاراکترها برای جستجو. ترتیب مهم نیست. |
| startindex | **int32_t** | [Index](../../index/) برای شروع جستجو. |
| count | **int32_t** | تعداد کاراکترهایی که باید جستجو شوند. |

### مقدار بازگشتی

[Index](../../index/) از اولین کاراکتر مطابق یا -1 اگر یافت نشود.

## مراجع مرتبط

* تعریف‌نوع [ArrayPtr](../../arrayptr/)
* کلاس [String](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)
---
title: LastIndexOfAny()
second_title: مرجع API Aspose.Slides برای C++
description: در تمام رشته به صورت عقب به عقب به دنبال هر یک از کاراکترهای پاس داده شده می‌گردد. کاراکتر آخر رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس کاراکتر قبلی را و به همین ترتیب ادامه می‌دهد. اندیس اولین تطابق یافت‌شده را برمی‌گرداند.
type: docs
weight: 664
url: /fa/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const متد

در تمام رشته به صورت عقب به عقب به دنبال هر یک از کاراکترهای پاس داده شده می‌گردد. کاراکتر آخر رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس کاراکتر قبلی را و به همین ترتیب ادامه می‌دهد. اندیس اولین تطابق یافت‌شده را برمی‌گرداند.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) کاراکترها برای جستجو. ترتیب مهم نیست. |

### مقدار بازگشت

[Index](../../index/) کاراکتر آخر مطابق یا -1 اگر یافت نشد.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const متد

در زیررشته به صورت عقب به عقب به دنبال هر یک از کاراکترهای پاس داده شده می‌گردد. کاراکتر آخر رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس کاراکتر قبلی را و به همین ترتیب ادامه می‌دهد. اندیس اولین تطابق یافت‌شده را برمی‌گرداند.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) کاراکترها برای جستجو. ترتیب مهم نیست. |
| startindex | **int32_t** | [Index](../../index/) برای شروع جستجو از. |

### مقدار بازگشت

[Index](../../index/) کاراکتر آخر مطابق یا -1 اگر یافت نشد.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const متد

در زیررشته به صورت عقب به عقب به دنبال هر یک از کاراکترهای پاس داده شده می‌گردد. کاراکتر آخر رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس کاراکتر قبلی را و به همین ترتیب ادامه می‌دهد. اندیس اولین تطابق یافت‌شده را برمی‌گرداند.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) کاراکترها برای جستجو. ترتیب مهم نیست. |
| startindex | **int32_t** | [Index](../../index/) برای شروع جستجو از. |
| count | **int32_t** | تعداد کاراکترهایی که باید بررسی شوند. |

### مقدار بازگشت

[Index](../../index/) کاراکتر آخر مطابق یا -1 اگر یافت نشد.

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
---
title: Split()
second_title: مرجع API Aspose.Slides برای C++
description: رشته را بر اساس کاراکتر تقسیم می‌کند.
type: docs
weight: 768
url: /fa/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const متد


رشته را بر اساس کاراکتر تقسیم می‌کند.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separator | char_t | کاراکتری که برای تقسیم رشته استفاده می‌شود. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## String::Split(char_t, int32_t, StringSplitOptions) const متد


رشته را بر اساس کاراکتر تقسیم می‌کند.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separator | char_t | کاراکتری که برای تقسیم رشته استفاده می‌شود. |
| count | **int32_t** | حداکثر تعداد زیررشته‌هایی که باید برگردانده شود. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## String::Split(char_t, char_t, StringSplitOptions) const متد


رشته را بر اساس یکی از دو کاراکتر تقسیم می‌کند.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorA | char_t | اولین کاراکتری که برای تقسیم رشته استفاده می‌شود. |
| separatorB | char_t | دومین کاراکتری که برای تقسیم رشته استفاده می‌شود. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const متد


رشته را بر اساس یکی از کاراکترهای مشخص شده تقسیم می‌کند.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) از کاراکترهای جداکننده. اگر خالی باشد، هر کاراکتر فضای خالی به عنوان جداکننده در نظر گرفته می‌شود. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const متد


رشته را بر اساس یکی از کاراکترهای مشخص شده تقسیم می‌کند.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) از کاراکترهای جداکننده. اگر خالی باشد، هر کاراکتر فضای خالی به عنوان جداکننده در نظر گرفته می‌شود. |
| count | **int32_t** | حداکثر تعداد زیررشته‌هایی که باید برگردانده شود. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## String::Split(const String\&, StringSplitOptions) const متد


رشته را بر اساس زیررشته تقسیم می‌کند.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separator | const [String](../)\& | زیررشته‌ای که به عنوان جداکننده عمل می‌کند. اگر خالی باشد، کاراکتر فضای خالی به عنوان جداکننده عمل می‌کند. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## String::Split(const String\&, int, StringSplitOptions) const متد


رشته را بر اساس زیررشته تقسیم می‌کند.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separator | const [String](../)\& | زیررشته‌ای که به عنوان جداکننده عمل می‌کند. اگر خالی باشد، کاراکتر فضای خالی به عنوان جداکننده عمل می‌کند. |
| count | int | حداکثر تعداد عناصر در آرایهٔ تقسیم‌ها. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const متد


رشته را بر اساس زیررشته تقسیم می‌کند.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) از رشته‌های جداکننده. اگر خالی باشد، هیچ تقسیم انجام نمی‌شود. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const متد


رشته را بر اساس زیررشته تقسیم می‌کند. در حال حاضر، فقط آرایهٔ جداکننده‌ها با صفر یا یک عنصر را پشتیبانی می‌کند.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) از رشته‌های جداکننده. اگر خالی باشد، هیچ تقسیم انجام نمی‌شود. |
| count | int | حداکثر تعداد عناصر در آرایهٔ تقسیم‌ها. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | گزینه‌های تقسیم. |

### مقدار بازگشت

[Array](../../array/) از زیررشته‌ها.

## موارد مرتبط

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
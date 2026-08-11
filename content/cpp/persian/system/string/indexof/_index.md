---
title: IndexOf()
second_title: مرجع API Aspose.Slides برای C++
description: جستجوی پیشرو زیررشته.
type: docs
weight: 625
url: /fa/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const method


جستجوی پیشرو زیررشته.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | زیررشته‌ای که باید جستجو شود. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) حالت. |

### مقدار بازگشت

[Index](../../index/) اولین زیررشته یافت‌شده یا -1 اگر یافت نشود. برای رشتهٔ جستجوی خالی، همیشه 0 برگردانده می‌شود.

## String::IndexOf(char_t, int) const method


جستجوی پیشرو کاراکتر.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| c | char_t | کاراکتری که باید جستجو شود. |
| startIndex | int | [Index](../../index/) برای شروع جستجو. |

### مقدار بازگشت

[Index](../../index/) موقعیت اولین کاراکتر از startIndex یا -1 اگر یافت نشود.

## String::IndexOf(char_t, int, int) const method


جستجوی پیشرو کاراکتر در زیررشته.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| c | char_t | کاراکتری که باید جستجو شود. |
| startIndex | int | [Index](../../index/) برای شروع جستجو. |
| count | int | تعداد کاراکترهایی که باید جستجو شود. |

### مقدار بازگشت

[Index](../../index/) موقعیت اولین کاراکتر از startIndex یا -1 اگر یافت نشود.

## String::IndexOf(const String\&, int) const method


جستجوی پیشرو زیررشته.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | زیررشته‌ای که باید جستجو شود. |
| startIndex | int | موقعیت در رشتهٔ منبع برای شروع جستجو. |

### مقدار بازگشت

[Index](../../index/) اولین زیررشته یافت‌شده یا -1 اگر یافت نشود. برای رشتهٔ جستجوی خالی، همیشه startIndex برگردانده می‌شود.

## String::IndexOf(const String\&, int, System::StringComparison) const method


جستجوی پیشرو زیررشته.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | زیررشته‌ای که باید جستجو شود. |
| startIndex | int | موقعیت در رشتهٔ منبع برای شروع جستجو. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) حالت. |

### مقدار بازگشت

[Index](../../index/) اولین زیررشته یافت‌شده یا -1 اگر یافت نشود. برای رشتهٔ جستجوی خالی، همیشه startIndex برگردانده می‌شود.

## String::IndexOf(const String\&, int, int, System::StringComparison) const method


جستجوی پیشرو زیررشته.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../)\& | زیررشته‌ای که باید جستجو شود. |
| startIndex | int | موقعیت در رشتهٔ منبع برای شروع جستجو. |
| count | int | تعداد کاراکترهایی که باید جستجو شود. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) حالت. |

### مقدار بازگشت

[Index](../../index/) اولین زیررشته یافت‌شده یا -1 اگر یافت نشود. برای رشتهٔ جستجوی خالی، همیشه startIndex برگردانده می‌شود.

## String::IndexOf(const String\&, int, int) const method


جستجوی پیشرو زیررشته.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | زیررشته‌ای که باید جستجو شود. |
| startIndex | int | موقعیت در رشتهٔ منبع برای شروع جستجو. |
| count | int | تعداد کاراکترهایی که باید جستجو شود. |

### مقدار بازگشت

[Index](../../index/) اولین زیررشته یافت‌شده یا -1 اگر یافت نشود. برای رشتهٔ جستجوی خالی، همیشه startIndex برگردانده می‌شود.

## موارد مرتبط

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
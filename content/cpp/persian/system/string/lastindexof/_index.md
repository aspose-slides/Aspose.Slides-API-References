---
title: LastIndexOf()
second_title: Aspose.Slides برای مرجع API C++
description: جستجوی معکوس زیررشته.
type: docs
weight: 651
url: /fa/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const متد

جستجوی معکوس زیررشته.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | زیررشته‌ای که جستجو می‌شود. |
| startIndex | int | موقعیتی در رشته منبع که جستجو از آن آغاز می‌شود. |

### مقدار بازگشت

[Index](../../index/) آخرین زیررشته یافت شده یا -1 اگر پیدا نشود. برای رشته جستجوی خالی، همیشه طول رشته را بر می‌گرداند.

## String::LastIndexOf(const String\&, System::StringComparison) const متد

جستجوی معکوس زیررشته.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | زیررشته‌ای که جستجو می‌شود. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | حالت [Comparison](../../comparison/). |

### مقدار بازگشت

[Index](../../index/) آخرین زیررشته یافت شده یا -1 اگر پیدا نشود. برای رشته جستجوی خالی، همیشه طول رشته را بر می‌گرداند.

## String::LastIndexOf(const String\&, int, System::StringComparison) const متد

جستجوی معکوس زیررشته.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | زیررشته‌ای که جستجو می‌شود. |
| startIndex | int | موقعیتی در رشته منبع که جستجو از آن آغاز می‌شود. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | حالت [Comparison](../../comparison/). |

### مقدار بازگشت

[Index](../../index/) آخرین زیررشته یافت شده یا -1 اگر پیدا نشود. برای رشته جستجوی خالی، همیشه طول رشته را بر می‌گرداند.

## String::LastIndexOf(const String\&, int, int, StringComparison) const متد

جستجوی معکوس زیررشته.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../)\& | زیررشته‌ای که جستجو می‌شود. |
| startIndex | int | موقعیتی در رشته منبع که جستجو از آن آغاز می‌شود. |
| count | int | تعداد کاراکترهایی که باید جستجو شود. |
| comparisonType | [StringComparison](../../stringcomparison/) | حالت [Comparison](../../comparison/). |

### مقدار بازگشت

[Index](../../index/) آخرین زیررشته یافت شده یا -1 اگر پیدا نشود. برای رشته جستجوی خالی، همیشه مقدار startIndex+count را بر می‌گرداند.

## String::LastIndexOf(char_t) const متد

جستجوی معکوس کاراکتر.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char_t | کاراکتری که جستجو می‌شود. |

### مقدار بازگشت

[Index](../../index/) موقعیت آخرین کاراکتر یا -1 اگر پیدا نشود.

## String::LastIndexOf(char_t, int32_t) const متد

جستجوی معکوس کاراکتر.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char_t | کاراکتری که جستجو می‌شود. |
| startIndex | **int32_t** | [Index](../../index/) برای شروع جستجو. |

### مقدار بازگشت

[Index](../../index/) موقعیت آخرین کاراکتر از startIndex به بعد یا -1 اگر پیدا نشود.

## String::LastIndexOf(char_t, int32_t, int32_t) const متد

جستجوی معکوس کاراکتر.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char_t | کاراکتری که جستجو می‌شود. |
| startIndex | **int32_t** | [Index](../../index/) برای شروع جستجو. |
| count | **int32_t** | تعداد کاراکترهایی که باید جستجو شود |

### مقدار بازگشت

[Index](../../index/) موقعیت آخرین کاراکتر از startIndex به بعد یا -1 اگر پیدا نشود.

## موارد مرتبط

* Enum [StringComparison](../../stringcomparison/)
* کلاس [String](../)
* فضای نام [System](../../)
* Library [Aspose.Slides](../../../)
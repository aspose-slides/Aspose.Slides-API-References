---
title: Equals()
second_title: Aspose.Slides برای C++ مرجع API
description: مقایسهٔ برابری رشته. چندین حالت ارائه‌شده توسط شمارش‌گر StringComparison پشتیبانی می‌شود.
type: docs
weight: 391
url: /fa/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const متد

[String](../) مقایسهٔ برابری. چندین حالت ارائه‌شده توسط شمارش‌گر StringComparison پشتیبانی می‌شود.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) برای مقایسه با مقدار فعلی. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) حالت (برای جزئیات به [System::StringComparison](../../stringcomparison/) مراجعه کنید). |

### مقدار بازگشت

true اگر رشته‌ها با استفاده از نوع مقایسهٔ انتخاب‌شده مطابقت داشته باشند، در غیر این صورت false.

## String::Equals(const String\&) const متد

[String](../) مقایسهٔ برابری. از حالت مقایسهٔ [System::StringComparison::Ordinal](../../stringcomparison/) استفاده می‌کند.

```cpp
bool System::String::Equals(const String &str) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) برای مقایسه با مقدار فعلی. |

### مقدار بازگشت

true اگر رشته‌ها مطابقت داشته باشند، در غیر این صورت false.

## String::Equals(const String\&, const String\&) متد

دو رشته را با استفاده از حالت مقایسهٔ Ordial برابر مقایسه می‌کند.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strA | const [String](../)\& | رشتهٔ اول برای مقایسه. |
| strB | const [String](../)\& | رشتهٔ دوم برای مقایسه. |

### مقدار بازگشت

true اگر رشته‌ها مطابقت داشته باشند، در غیر این صورت false.

## String::Equals(const String\&, const String\&, System::StringComparison) متد

دو رشته را برابر مقایسه می‌کند.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strA | const [String](../)\& | رشتهٔ اول برای مقایسه. |
| strB | const [String](../)\& | رشتهٔ دوم برای مقایسه. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) حالت. |

### مقدار بازگشت

true اگر رشته‌ها مطابقت داشته باشند، در غیر این صورت false.

## موارد مرتبط

* شمارش [StringComparison](../../stringcomparison/)
* کلاس [String](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)
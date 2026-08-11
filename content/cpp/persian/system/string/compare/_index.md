---
title: Compare()
second_title: مرجع API Aspose.Slides برای C++
description: عملگر کمتر-برابر-بزرگ دو زیررشته را مقایسه می‌کند.
type: docs
weight: 820
url: /fa/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) method


عملگر کمتر-برابر-بزرگ دو زیررشته را مقایسه می‌کند.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strA | const [String](../)\& | رشتهٔ اول برای مقایسه. |
| indexA | int | شروع زیررشتهٔ اول. |
| strB | const [String](../)\& | رشتهٔ دوم برای مقایسه. |
| indexB | int | شروع زیررشتهٔ دوم. |
| length | int | تعداد کاراکترهای مورد مقایسه. |
| ignoreCase | **bool** | مشخص می‌کند آیا مقایسه بدون در نظر گرفتن حروف بزرگ و کوچک باشد. |

### مقدار بازگشت

مقدار منفی اگر زیررشتهٔ اول کمتر از دوم باشد، صفر اگر برابر باشند، و مقدار مثبت در غیر اینصورت.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method


عملگر کمتر-برابر-بزرگ دو زیررشته را مقایسه می‌کند.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strA | const [String](../)\& | رشتهٔ اول برای مقایسه. |
| indexA | int | شروع زیررشتهٔ اول. |
| strB | const [String](../)\& | رشتهٔ دوم برای مقایسه. |
| indexB | int | شروع زیررشتهٔ دوم. |
| length | int | تعداد کاراکترهای مورد مقایسه. |
| ignoreCase | **bool** | مشخص می‌کند آیا مقایسه بدون در نظر گرفتن حروف بزرگ و کوچک باشد. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگی که برای مقایسه استفاده می‌شود. |

### مقدار بازگشت

مقدار منفی اگر زیررشتهٔ اول کمتر از دوم باشد، صفر اگر برابر باشند، و مقدار مثبت در غیر اینصورت.

## String::Compare(const String\&, const String\&, System::StringComparison) method


عملگر کمتر-برابر-بزرگ دو رشته را مقایسه می‌کند.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strA | const [String](../)\& | رشتهٔ اول برای مقایسه. |
| strB | const [String](../)\& | رشتهٔ دوم برای مقایسه. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) حالت. |

### مقدار بازگشت

مقدار منفی اگر زیررشتهٔ اول کمتر از دوم باشد، صفر اگر برابر باشند، و مقدار مثبت در غیر اینصورت.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) method


عملگر کمتر-برابر-بزرگ دو رشته را مقایسه می‌کند.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strA | const [String](../)\& | رشتهٔ اول برای مقایسه. |
| indexA | int | شروع زیررشتهٔ اول. |
| strB | const [String](../)\& | رشتهٔ دوم برای مقایسه. |
| indexB | int | شروع زیررشتهٔ دوم. |
| length | int | تعداد کاراکترهای مورد مقایسه. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) حالت. |

### مقدار بازگشت

مقدار منفی اگر زیررشتهٔ اول کمتر از دوم باشد، صفر اگر برابر باشند، و مقدار مثبت در غیر اینصورت.

## String::Compare(const String\&, const String\&, bool) method


عملگر کمتر-برابر-بزرگ دو رشته را مقایسه می‌کند.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strA | const [String](../)\& | رشتهٔ اول برای مقایسه. |
| strB | const [String](../)\& | رشتهٔ دوم برای مقایسه. |
| ignoreCase | **bool** | مشخص می‌کند آیا مقایسه بدون در نظر گرفتن حروف بزرگ و کوچک باشد. |

### مقدار بازگشت

مقدار منفی اگر زیررشتهٔ اول کمتر از دوم باشد، صفر اگر برابر باشند، و مقدار مثبت در غیر اینصرف.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method


عملگر کمتر-برابر-بزرگ دو رشته را مقایسه می‌کند.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strA | const [String](../)\& | رشتهٔ اول برای مقایسه. |
| strB | const [String](../)\& | رشتهٔ دوم برای مقایسه. |
| ignoreCase | **bool** | مشخص می‌کند آیا مقایسه بدون در نظر گرفتن حروف بزرگ و کوچک باشد. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگی که برای مقایسه استفاده می‌شود. |

### مقدار بازگشت

مقدار منفی اگر زیررشتهٔ اول کمتر از دوم باشد، صفر اگر برابر باشند، و مقدار مثبت در غیر اینصورت.

## موارد مرتبط

* شمارشی [StringComparison](../../stringcomparison/)
* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)
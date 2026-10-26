---
title: Compare()
second_title: Aspose.Slides برای C++ مرجع API
description: رشته‌ها را مقایسه می‌کند. پیاده‌سازی نشده است.
type: docs
weight: 66
url: /fa/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const متد

رشته‌ها را مقایسه می‌کند. پیاده‌سازی نشده است.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | رشتهٔ سمت چپ. |
| string2 | const [String](../../../system/string/)\& | رشتهٔ سمت راست. |

### مقدار بازگشت

اگر رشتهٔ سمت چپ قبل از رشتهٔ سمت راست باشد مقدار منفی، اگر برابر باشند صفر، در غیر اینصورت مقدار مثبت.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const متد

رشته‌ها را مقایسه می‌کند. فقط حالت‌های Ordinal و OrdinalIgnoreCase پشتیبانی می‌شوند.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | رشتهٔ سمت چپ. |
| b | const [String](../../../system/string/)\& | رشتهٔ سمت راست. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) نوع مقایسه. |

### مقدار بازگشت

اگر رشتهٔ سمت چپ قبل از رشتهٔ سمت راست باشد مقدار منفی، اگر برابر باشند صفر، در غیر اینصورت مقدار مثبت.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const متد

بخشی از یک رشته را با بخشی از رشتهٔ دوم مقایسه می‌کند. پیاده‌سازی نشده است.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | رشتهٔ اول. |
| offset1 | int | اندیس شروع کاراکترها در **string1**. |
| length1 | int | تعداد کاراکترهای **string1** برای مقایسه. |
| string2 | const [String](../../../system/string/)\& | رشتهٔ دوم. |
| offset2 | int | اندیس شروع کاراکترها در **string2**. |
| length2 | int | تعداد کاراکترهای **string2** برای مقایسه. |

### مقدار بازگشت

اگر بخش اول رشته قبل از بخش دوم رشته باشد مقدار منفی، اگر برابر باشند صفر، در غیر اینصورت مقدار مثبت.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const متد

بخش انتهایی یک رشته را با بخش انتهایی رشتهٔ دوم با استفاده از روش‌های مقایسهٔ رشته‌ای مقایسه می‌کند. پیاده‌سازی نشده است.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | رشتهٔ اول. |
| offset1 | int | اندیس شروع کاراکترها در **string1**. |
| string2 | const [String](../../../system/string/)\& | رشتهٔ دوم. |
| offset2 | int | اندیس شروع کاراکترها در **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) گزینه‌های مقایسه. |

### مقدار بازگشت

اگر بخش اول رشته قبل از بخش دوم رشته باشد مقدار منفی، اگر برابر باشند صفر، در غیر اینصورت مقدار مثبت.

## CompareInfo::Compare(const String\&, int, const String\&, int) const متد

بخش انتهایی یک رشته را با بخش انتهایی رشتهٔ دوم مقایسه می‌کند. پیاده‌سازی نشده است.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | رشتهٔ اول. |
| offset1 | int | اندیس شروع کاراکترها در **string1**. |
| string2 | const [String](../../../system/string/)\& | رشتهٔ دوم. |
| offset2 | int | اندیس شروع کاراکترها در **string2**. |

### مقدار بازگشت

اگر بخش اول رشته قبل از بخش دوم رشته باشد مقدار منفی، اگر برابر باشند صفر، در غیر اینصورت مقدار مثبت.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const متد

بخشی از یک رشته را با بخشی از رشتهٔ دوم با استفاده از روش‌های مقایسهٔ رشته‌ای مقایسه می‌کند. پیاده‌سازی نشده است.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | رشتهٔ اول. |
| offset1 | int | اندیس شروع کاراکترها در **string1**. |
| length1 | int | تعداد کاراکترهای **string1** برای مقایسه. |
| string2 | const [String](../../../system/string/)\& | رشتهٔ دوم. |
| offset2 | int | اندیس شروع کاراکترها در **string2**. |
| length2 | int | تعداد کاراکترهای **string2** برای مقایسه. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) گزینه‌های مقایسه. |

### مقدار بازگشت

اگر بخش اول رشته قبل از بخش دوم رشته باشد مقدار منفی، اگر برابر باشند صفر، در غیر اینصورت مقدار مثبت.

## مراجع

* enum [CompareOptions](../../compareoptions/)
* کلاس [String](../../../system/string/)
* کلاس [CompareInfo](../)
* فضای نام [System::Globalization](../../)
* کتابخانه [Aspose.Slides](../../../)
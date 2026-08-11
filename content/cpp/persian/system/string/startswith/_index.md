---
title: StartsWith()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص شده شروع می‌شود.
type: docs
weight: 469
url: /fa/system/string/startswith/
---
## String::StartsWith(const String\&) const متد

بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص شده شروع می‌شود یا نه.

```cpp
bool System::String::StartsWith(const String &value) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../)\& | رشتهٔ جستجو. |

### مقدار بازگشت

true اگر رشته با زیررشتهٔ مشخص شده شروع شود، در غیر این صورت false.

## String::StartsWith(const String\&, System::StringComparison) const متد

بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص شده شروع می‌شود یا نه.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../)\& | رشتهٔ جستجو. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | حالت [Comparison](../../comparison/)، برای جزئیات [System::StringComparison](../../stringcomparison/) را ببینید. |

### مقدار بازگشت

true اگر رشته با زیررشتهٔ مشخص شده شروع شود، در غیر این صورت false.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const متد

بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص شده شروع می‌شود یا نه.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../)\& | رشتهٔ جستجو. |
| ignoreCase | **bool** | مشخص می‌کند که آیا مقایسه بدون حساسیت به حروف باشد یا نه. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگ مورد استفاده در هنگام مقایسهٔ رشته. |

### مقدار بازگشت

true اگر رشته با زیررشتهٔ مشخص شده شروع شود، در غیر این صورت false.

## موارد مرتبط

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
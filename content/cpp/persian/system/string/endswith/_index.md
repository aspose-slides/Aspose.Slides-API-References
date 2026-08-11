---
title: EndsWith()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص شده به پایان می‌رسد.
type: docs
weight: 482
url: /fa/system/string/endswith/
---
## String::EndsWith(const String&) const متد

بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص شده به پایان می‌رسد یا خیر.

```cpp
bool System::String::EndsWith(const String &value) const
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | رشتهٔ جستجو. |

### مقدار بازگشت

اگر رشته با زیررشتهٔ مشخص شده به پایان برسد true و در غیر این صورت false.

## String::EndsWith(const String&, System::StringComparison) const متد

بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص شده به پایان می‌رسد یا خیر.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | رشتهٔ جستجو. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) حالت، برای جزئیات به [System::StringComparison](../../stringcomparison/) مراجعه کنید. |

### مقدار بازگشت

اگر رشته با زیررشتهٔ مشخص شده به پایان برسد true و در غیر این صورت false.

## String::EndsWith(const String&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const متد

بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص شده به پایان می‌رسد یا خیر.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | رشتهٔ جستجو. |
| ignoreCase | **bool** | مشخص می‌کند که آیا مقایسه بدون در نظر گرفتن حروف بزرگ و کوچک باشد یا نه. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگی که هنگام مقایسهٔ رشته استفاده می‌شود. |

### مقدار بازگشت

اگر رشته با زیررشتهٔ مشخص شده به پایان برسد true و در غیر این صورت false.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
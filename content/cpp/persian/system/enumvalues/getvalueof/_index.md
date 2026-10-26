---
title: GetValueOf()
second_title: Aspose.Slides برای مرجع API C++
description: مقدار جعبه‌بندی‌شدهٔ ثابت enum با نام مشخص‌شده را برمی‌گرداند.
type: docs
weight: 53
url: /fa/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const متد


مقدار جعبه‌بندی‌شدهٔ ثابت enum با نام مشخص‌شده را برمی‌گرداند.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| str | const [String](../../string/)\& | نام ثابت enum |
| ignoreCase | **bool** | مشخص می‌کند که آیا هنگام تفسیر نام ثابت enum، به حروف بزرگ و کوچک اهمیت داده شود یا نه |

### مقدار بازگشتی

مقدار جعبه‌بندی‌شدهٔ ثابت enum که نام آن در **str** مشخص شده است.

## EnumValues::GetValueOf(long) const متد


مقدار جعبه‌بندی‌شدهٔ ثابت enum با مقدار مشخص‌شده را برمی‌گرداند.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| val | long | مقدار ثابت enum |

### مقدار بازگشتی

مقدار جعبه‌بندی‌شدهٔ ثابت enum که vakye آن در **str** مشخص شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [Object](../../object/)
* کلاس [String](../../string/)
* کلاس [EnumValues](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)
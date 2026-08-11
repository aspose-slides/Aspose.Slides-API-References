---
title: KeyValuePair
second_title: Aspose.Slides برای مرجع API C++
description: "جفت کلید و مقدار. این نوع باید در پشته تخصیص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 378
url: /fa/system.collections.generic/keyvaluepair/
---
## کلاس KeyValuePair

جفت کلید و مقدار. این نوع باید در پشته تخصیص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../../system/smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## متدها

| متد | توضیح |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | کلید را برمی‌گرداند. |
| const TValue\& [get_Value](./get_value/)() const | مقدار را برمی‌گرداند. |
| int [GetHashCode](./gethashcode/)() const | هش جفت کلید-مقدار را با XOR هش‌های کلید و مقدار محاسبه می‌کند. |
| **bool** [IsNull](./isnull/)() const | همیشه false را برمی‌گرداند. |
| [KeyValuePair](./keyvaluepair/)() | مقداردهی اولیه جفت کلید-مقدار null. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | سازنده. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | سازنده تبدیل نوع. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | پچ برای کلاس‌های ارث‌برده از IComparer<KeyValuePair<TKey, TValue>>، هیچ چیزی را مقایسه نمی‌کند. |
| [String](../../system/string/) [ToString](./tostring/)() const | جفت کلید-مقدار را به رشته تبدیل می‌کند. |

## موارد مرتبط

* فضای نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)
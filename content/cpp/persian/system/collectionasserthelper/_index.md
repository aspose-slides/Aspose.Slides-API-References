---
title: CollectionAssertHelper
second_title: Aspose.Slides برای مرجع API C++
description: API کمکی برای عملیات مرتبط با مجموعه‌ها.
type: docs
weight: 1548
url: /fa/system/collectionasserthelper/
---
## CollectionAssertHelper struct

API کمکی برای عملیات مرتبط با مجموعه‌ها.

```cpp
class CollectionAssertHelper
```

## متدها

| متد | توضیح |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | بررسی می‌کند که تمام عناصر مجموعه تابع پیش شرط را رعایت کنند. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | بررسی می‌کند که هر عنصر از مجموعه تابع پیش شرط را رعایت کند. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | دو مجموعه را برای نمایش پیام سریال‌سازی می‌کند. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | مجموعه را به رشته تبدیل می‌کند با ادغام نمایش‌های رشته‌ای عناصر. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | تفاوت ('diff') بین دو مجموعه را محاسبه می‌کند. برای هر عنصر از هر مجموعه به عنوان کلید، مقدار حاصل مثبت خواهد بود اگر عنصر در مجموعه "expected" بیشتر رخ دهد، منفی اگر در مجموعه "actual" بیشتر رخ دهد، و صفر اگر در هر دو مجموعه تعداد برابر داشته باشد. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | رشته را برای استفاده به عنوان متن پیام قالب‌بندی می‌کند. |
## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)
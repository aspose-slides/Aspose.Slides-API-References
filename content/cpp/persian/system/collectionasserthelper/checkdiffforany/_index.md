---
title: CheckDiffForAny()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که هر عنصر مجموعه‌ای پیش‌شرط را برآورده می‌کند.
type: docs
weight: 27
url: /fa/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method


بررسی می‌کند که هر عنصر مجموعه‌ای پیش‌شرط را برآورده می‌کند.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | پیش‌شرط برای بررسی. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | مقادیر برای بررسی. |

### مقدار برگشتی

True اگر بررسی برای هر عنصر موفق باشد، false اگر همه عبور کنند.

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)
---
title: CheckDiffForAll()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که تمام عناصر مجموعه با پیش‌شرط مطابقت دارند.
type: docs
weight: 14
url: /fa/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) متد

بررسی می‌کند که تمام عناصر مجموعه با پیش‌شرط مطابقت داشته باشند.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | پیش‌شرط برای بررسی. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | مقادیری که باید بررسی شوند. |

### مقدار بازگشت

در صورتی که بررسی برای هر عنصری شکست بخورد false و اگر همه عبور کنند true.

## نگاه کنید به

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
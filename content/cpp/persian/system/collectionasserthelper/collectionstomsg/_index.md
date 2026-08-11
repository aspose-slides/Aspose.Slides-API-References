---
title: CollectionsToMsg()
second_title: مرجع API Aspose.Slides برای C++
description: دو مجموعه را برای نمایش در پیام سریال‌سازی می‌کند.
type: docs
weight: 53
url: /fa/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) متد

دو مجموعه را برای نمایش در پیام سریال‌سازی می‌کند.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عنصر مجموعه مورد انتظار. |
| T2 | نوع عنصر مجموعه واقعی. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | یک رشتهٔ سفارشی که قبل از مقدار مورد انتظار در پیام نهایی درج می‌شود |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | مجموعهٔ مورد انتظار. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | مجموعهٔ واقعی. |

### مقدار بازگشتی

پیام کاربرپسند درباره محتوای مجموعه‌ها.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* ساختار [CollectionAssertHelper](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)
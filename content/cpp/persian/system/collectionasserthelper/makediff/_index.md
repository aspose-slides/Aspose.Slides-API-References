---
title: MakeDiff()
second_title: مرجع API Aspose.Slides برای C++
description: محاسبه 'diff' بین دو مجموعه. برای هر عنصر از هر مجموعه به‌عنوان کلید، مقدار نتیجه مثبت خواهد بود اگر عنصر بیشتر در \"expected\" مجموعه ظاهر شود، منفی اگر بیشتر در \"actual\" مجموعه ظاهر شود، و صفر اگر در هر دو مجموعه به‌عدد برابر ظاهر شود.
type: docs
weight: 1
url: /fa/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) متد


قابلیت محاسبه 'diff' بین دو مجموعه. برای هر عنصر از هر مجموعه به‌عنوان کلید، مقدار نتیجه مثبت خواهد بود اگر عنصر بیشتر در مجموعه "expected" ظاهر شود، منفی اگر بیشتر در مجموعه "actual" ظاهر شود، و صفر اگر در هر دو مجموعه به تعداد برابر ظاهر شود.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عنصر مجموعه مورد انتظار. |
| T2 | نوع عنصر مجموعه واقعی. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | مجموعه مورد انتظار. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | مجموعه واقعی. |

### مقدار بازگشتی

نقشه‌ای از نتایج مقایسه بر اساس مقدار، طبق قوانین بالا.

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
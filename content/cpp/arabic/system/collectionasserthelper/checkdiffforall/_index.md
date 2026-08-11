---
title: CheckDiffForAll()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يتحقق من أن جميع عناصر المجموعة تلتزم بالشرط.
type: docs
weight: 14
url: /ar/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) طريقة

يتحقق من أن جميع عناصر المجموعة تلتزم بالشرط.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | الشرط للتحقق منه. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | القيم للتحقق منها. |

### قيمة الإرجاع

خطأ إذا فشل الفحص لأي عنصر، صحيح إذا نجح جميع العناصر.

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* فئة [ICollection](../../../system.collections.generic/icollection/)
* بنية [CollectionAssertHelper](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)
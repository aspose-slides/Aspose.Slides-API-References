---
title: CheckDiffForAny()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق من أن أي عنصر في المجموعة يطابق الشرط.
type: docs
weight: 27
url: /ar/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) طريقة

يتحقق من أن أي عنصر في المجموعة يطابق الشرط.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | الشرط للتحقق منه. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | القيم للتحقق منها. |

### قيمة الإرجاع

صحيح إذا نجح الفحص لأي عنصر، خطأ إذا فشل جميع العناصر.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [ICollection](../../../system.collections.generic/icollection/)
* بنية [CollectionAssertHelper](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)
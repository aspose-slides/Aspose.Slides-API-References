---
title: Remove()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل الظهور الأول لكائن معين من ICollection.
type: docs
weight: 339
url: /ar/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) طريقة


يزيل الظهور الأول لكائن محدد من [ICollection](../../../system.collections.generic/icollection/).

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```


### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | الكائن المراد إزالته من [ICollection](../../../system.collections.generic/icollection/). |

### قيمة الإرجاع

صحيح إذا تم إزالة *item* بنجاح من [ICollection](../../../system.collections.generic/icollection/)؛ وإلا، خطأ. تُعيد هذه الطريقة أيضًا خطأ إذا لم يُعثر على *item* في [ICollection](../../../system.collections.generic/icollection/) الأصلي.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IImageTransformOperation](../../iimagetransformoperation/)
* فئة [ImageTransformOperationCollection](../)
* مساحة الاسم [Aspose::Slides::Effects](../../)
* مكتبة [Aspose.Slides](../../../)
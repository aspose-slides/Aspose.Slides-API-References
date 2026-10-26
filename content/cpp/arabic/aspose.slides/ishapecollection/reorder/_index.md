---
title: Reorder()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال.
type: docs
weight: 300
url: /ar/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) طريقة

ينقل الشكل المحدد إلى موقع جديد داخل مجموعة الأشكال.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### المتطلبات

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس المستهدف الصفري حيث سيتم وضع الشكل. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | ال[IShape](../../ishape/) لنقله داخل المجموعة. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) طريقة

ينقل الأشكال المحددة داخل مجموعة الأشكال، موضعًا إياها بدءًا من الفهرس المعطى.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### المتطلبات

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس المستهدف الصفري حيث سيتم وضع الشكل الأول المحدد؛ تتبع الأشكال اللاحقة بالترتيب المقدم. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | واحدة أو أكثر من مثيلات [IShape](../../ishape/) لنقلها داخل المجموعة. |

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IShape](../../ishape/)
* فئة [IShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
---
title: Reorder()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال.
type: docs
weight: 339
url: /ar/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) طريقة

ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الهدف صفر-الأساس حيث سيتم وضع الشكل. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) لنقله داخل المجموعة. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) طريقة

ينقل الأشكال المحددة داخل مجموعة الأشكال، ويضعها بدءًا من الفهرس المحدد.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الهدف صفر-الأساس حيث سيتم وضع الشكل المحدد الأول؛ تتبع الأشكال اللاحقة بالترتيب المذكور. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | واحد أو أكثر من كائنات [IShape](../../ishape/) لنقلها داخل المجموعة. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IShape](../../ishape/)
* فئة [ShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
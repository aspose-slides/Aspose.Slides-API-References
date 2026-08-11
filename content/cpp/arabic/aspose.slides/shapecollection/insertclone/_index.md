---
title: InsertClone()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء نسخة من الشكل المحدد وإدراجها في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 560
url: /ar/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) طريقة

إنشاء نسخة من الشكل المحدد وإدراجها في مجموعة الأشكال في الفهرس المحدد.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي سيتم إدراج الشكل المستنسخ عنده. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) لاستنساخه. |
| x | **float** | الإحداثي x لإطار الشكل المستنسخ، بالنقاط. |
| y | **float** | الإحداثي y لإطار الشكل المستنسخ، بالنقاط. |
| width | **float** | عرض إطار الشكل المستنسخ، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل المستنسخ، بالنقاط. |

### قيمة الإرجاع

الـ [IShape](../../ishape/) الذي أنشئ حديثًا.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) طريقة

إنشاء نسخة من الشكل المحدد وإدراجها في مجموعة الأشكال في الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي سيتم إدراج الشكل المستنسخ عنده. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) لاستنساخه. |
| x | **float** | الإحداثي x لإطار الشكل المستنسخ، بالنقاط. |
| y | **float** | الإحداثي y لإطار الشكل المستنسخ، بالنقاط. |

### قيمة الإرجاع

الـ [IShape](../../ishape/) الذي أنشئ حديثًا.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) طريقة

إنشاء نسخة من الشكل المحدد وإدراجها في مجموعة الأشكال في الفهرس المحدد. يحتفظ الشكل المستنسخ بموقع وحجم الأصل.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي سيتم إدراج الشكل المستنسخ عنده. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) لاستنساخه. |

### قيمة الإرجاع

الـ [IShape](../../ishape/) الذي أنشئ حديثًا.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IShape](../../ishape/)
* فئة [ShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
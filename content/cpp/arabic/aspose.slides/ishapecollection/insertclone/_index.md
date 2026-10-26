---
title: InsertClone()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: ينشئ نسخة من الشكل المحدد ويُدخلها في مجموعة الأشكال في الفهرس المحدد.
type: docs
weight: 508
url: /ar/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) طريقة


ينشئ نسخة من الشكل المحدد ويُدخلها في مجموعة الأشكال في الفهرس المحدد.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري-المستند الذي يُدخل فيه الشكل المستنسخ. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) الذي سيُنسخ. |
| x | **float** | إحداثي x لإطار الشكل المستنسخ، بالنقاط. |
| y | **float** | إحداثي y لإطار الشكل المستنسخ، بالنقاط. |
| width | **float** | عرض إطار الشكل المستنسخ، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل المستنسخ، بالنقاط. |

### قيمة الإرجاع

[IShape](../../ishape/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) طريقة


ينشئ نسخة من الشكل المحدد ويُدخلها في مجموعة الأشكال في الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع *sourceShape*.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري-المستند الذي يُدخل فيه الشكل المستنسخ. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) الذي سيُنسخ. |
| x | **float** | إحداثي x لإطار الشكل المستنسخ، بالنقاط. |
| y | **float** | إحداثي y لإطار الشكل المستنسخ، بالنقاط. |

### قيمة الإرجاع

[IShape](../../ishape/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) طريقة


ينشئ نسخة من الشكل المحدد ويُدخلها في مجموعة الأشكال في الفهرس المحدد. يحتفظ الشكل المستنسخ بموقعه وحجمه الأصلي.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري-المستند الذي يُدخل فيه الشكل المستنسخ. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) الذي سيُنسخ. |

### قيمة الإرجاع

[IShape](../../ishape/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IShape](../../ishape/)
* فئة [IShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
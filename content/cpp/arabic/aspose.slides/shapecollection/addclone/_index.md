---
title: AddClone()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء نسخة من الشكل المحدد وإضافتها إلى نهاية مجموعة الأشكال.
type: docs
weight: 547
url: /ar/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) طريقة

إنشاء نسخة من الشكل المحدد وإضافتها إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الشكل لاستنساخه. |
| x | **float** | الإحداثي x لإطار الشكل الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار الشكل الجديد، بالنقاط. |
| width | **float** | عرض إطار الشكل الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل الجديد، بالنقاط. |

### قيمة الإرجاع

العنصر الذي تم إنشاؤه حديثًا [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) طريقة

إنشاء نسخة من الشكل المحدد وإضافتها إلى نهاية مجموعة الأشكال. يحتفظ الشكل الجديد بعرض وارتفاع الـ *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الشكل لاستنساخه. |
| x | **float** | الإحداثي x لإطار الشكل الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار الشكل الجديد، بالنقاط. |

### قيمة الإرجاع

العنصر الذي تم إنشاؤه حديثًا [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) طريقة

إنشاء نسخة من الشكل المحدد وإضافتها إلى نهاية مجموعة الأشكال. يظل الشكل المستنسخ في موقع وحجم الأصلي.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) لاستنساخه. |

### قيمة الإرجاع

العنصر الذي تم إنشاؤه حديثًا [IShape](../../ishape/).

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
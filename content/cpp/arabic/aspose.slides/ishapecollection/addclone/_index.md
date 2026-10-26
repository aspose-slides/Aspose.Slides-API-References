---
title: AddClone()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال.
type: docs
weight: 495
url: /ar/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) طريقة

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الشكل المراد نسخة. |
| x | **float** | الإحداثي x لإطار الشكل المستنسخ، بوحدات النقاط. |
| y | **float** | الإحداثي y لإطار الشكل المستنسخ، بوحدات النقاط. |
| width | **float** | عرض إطار الشكل المستنسخ، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الشكل المستنسخ، بوحدات النقاط. |

### قيمة الإرجاع

الـ [IShape](../../ishape/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) طريقة

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. الشكل الجديد يحتفظ بعرض وارتفاع *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) لنسخه. |
| x | **float** | الإحداثي x لإطار الشكل المستنسخ، بوحدات النقاط. |
| y | **float** | الإحداثي y لإطار الشكل المستنسخ، بوحدات النقاط. |

### قيمة الإرجاع

الـ [IShape](../../ishape/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) طريقة

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. الشكل المستنسخ يحتفظ بموقع وحجم الأصل.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | الـ [IShape](../../ishape/) لنسخه. |

### قيمة الإرجاع

الـ [IShape](../../ishape/) الذي تم إنشاؤه حديثًا.

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IShape](../../ishape/)
* الفئة [IShapeCollection](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)
---
title: InsertClone()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نسخة من عمود القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.
type: docs
weight: 27
url: /ar/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) طريقة

ينشئ نسخة من عمود القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس العمود الجديد. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) الذي يستخدم كقالب. |
| withAttachedColumns | **bool** | صحيح لنسخ أيضاً جميع الأعمدة المرتبطة بعمود القالب. |

### قيمة الإرجاع

الأعمدة المدخلة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IColumn](../../icolumn/)
* فئة [IColumnCollection](../)
* مساحة الأسماء [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)
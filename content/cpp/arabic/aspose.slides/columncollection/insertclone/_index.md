---
title: InsertClone()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ نسخة من العمود القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.
type: docs
weight: 66
url: /ar/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) طريقة

ينشئ نسخة من العمود القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس العمود الجديد. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) الذي يُستخدم كقالب. |
| withAttachedColumns | **bool** | True لنسخ أيضًا جميع الأعمدة المرفقة بالعمود القالب. |

### قيمة الإرجاع

الأعمدة المدرجة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IColumn](../../icolumn/)
* فئة [ColumnCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
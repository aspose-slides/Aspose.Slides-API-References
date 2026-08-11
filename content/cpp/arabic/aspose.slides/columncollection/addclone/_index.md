---
title: AddClone()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل جدول.
type: docs
weight: 53
url: /ar/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) طريقة

ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل جدول.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### معلمات

| Parameter | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) التي تُستخدم كقالب. |
| withAttachedColumns | **bool** | True لنسخ جميع الأعمدة المرتبطة بصف القالب أيضًا. |

### قيمة الإرجاع

الأعمدة المضافة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IColumn](../../icolumn/)
* فئة [ColumnCollection](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
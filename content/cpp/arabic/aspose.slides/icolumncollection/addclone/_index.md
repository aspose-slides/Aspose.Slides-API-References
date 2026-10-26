---
title: AddClone()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل جدول.
type: docs
weight: 14
url: /ar/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) طريقة

ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل جدول.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) التي تُستخدم كقالب. |
| withAttachedColumns | **bool** | True لنسخ جميع الأعمدة المرتبطة بصف القالب أيضا. |

### قيمة الإرجاع

الأعمدة المضافة.

## انظر أيضا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IColumn](../../icolumn/)
* فئة [IColumnCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
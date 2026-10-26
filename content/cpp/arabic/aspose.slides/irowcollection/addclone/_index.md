---
title: AddClone()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل الجدول.
type: docs
weight: 14
url: /ar/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) طريقة

ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل الجدول.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### المعلمات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) الذي يُستخدم كقالب. |
| withAttachedRows | **bool** | True لنسخ أيضًا جميع الصفوف المرفقة بصف القالب. |

### قيمة الإرجاع

الصفوف المضافة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: InsertClone()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: ينشئ نسخة من صف القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.
type: docs
weight: 27
url: /ar/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) طريقة

ينشئ نسخة من صف القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الصف الجديد. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) التي تُستخدم كقالب. |
| withAttachedRows | **bool** | True لنسخ جميع الصفوف المرفقة بصف القالب أيضًا. |

### قيمة الإرجاع

الصفوف المُدرجة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IRow](../../irow/)
* فئة [IRowCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
---
title: AddClone()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل الجدول.
type: docs
weight: 53
url: /ar/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) طريقة


ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل الجدول.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) الذي يُستخدم كقالب. |
| withAttachedRows | **bool** | صحيح لنسخ جميع الصفوف المرفقة بصف القالب أيضاً. |

### قيمة الإرجاع

الصفوف المضافة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IRow](../../irow/)
* فئة [RowCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
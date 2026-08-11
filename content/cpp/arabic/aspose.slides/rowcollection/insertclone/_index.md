---
title: InsertClone()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُنشئ نسخة من صف القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.
type: docs
weight: 66
url: /ar/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) method

يُنشئ نسخة من صف القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | فهرس الصف الجديد. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) التي تُستخدم كقالب. |
| withAttachedRows | **bool** | صحيح لنسخ أيضًا جميع الصفوف المرتبطة بصف القالب. |

## قيمة الإرجاع

الصفوف المُدرجة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IRow](../../irow/)
* الفئة [RowCollection](../)
* المجال [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)
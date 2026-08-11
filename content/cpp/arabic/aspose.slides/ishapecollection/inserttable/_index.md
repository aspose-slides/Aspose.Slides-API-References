---
title: InsertTable()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد.
type: docs
weight: 443
url: /ar/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) طريقة

ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي سيتم عنده إدراج الجدول. |
| x | **float** | الإحداثي x للجدول، بوحدات النقاط. |
| y | **float** | الإحداثي y للجدول، بوحدات النقاط. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | مصوفة من القيم المزدوجة تمثل عرض أعمدة الجدول، بوحدات النقاط. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | مصوفة من القيم المزدوجة تمثل ارتفاع صفوف الجدول، بوحدات النقاط. |

### قيمة الإرجاع

الكائن [ITable](../../itable/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ITable](../../itable/)
* فئة [IShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
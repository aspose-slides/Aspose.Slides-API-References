---
title: InsertTable()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد.
type: docs
weight: 482
url: /ar/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) طريقة

ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج الجدول. |
| x | **float** | الإحداثي س للجدول، بوحدة النقاط. |
| y | **float** | الإحداثي ص للجدول، بوحدة النقاط. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | مصفوفة من القيم المزدوجة تمثل عرض أعمدة الجدول، بوحدة النقاط. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | مصفوفة من القيم المزدوجة تمثل ارتفاع صفوف الجدول، بوحدة النقاط. |

### قيمة الإرجاع

[ITable](../../itable/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ITable](../../itable/)
* فئة [ShapeCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)
---
title: Add()
second_title: مرجع API Aspose.Slides للغة C++
description: إذا كانت الفئة موجودة في المجموعة، يتم إرجاعها. إذا لم تكن كذلك، يتم إنشاء فئة مخطط جديدة من IChartDataCell وإضافتها إلى المجموعة.
type: docs
weight: 92
url: /ar/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) طريقة

إذا كانت الفئة موجودة في المجموعة، تُرجِعها. وإلا يُنشئ فئة مخطط جديدة من [IChartDataCell](../../ichartdatacell/) ويضيفها إلى المجموعة.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) تُستخدم لإنشاء فئة مخطط. |

### قيمة الإرجاع

الفئة المضافة أو الموجودة.

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) طريقة

ينشئ [ChartCategory](../../chartcategory/) جديدًا من القيمة ويضيفه إلى المجموعة.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | القيمة. |

### قيمة الإرجاع

تمت إضافة [IChartCategory](../../ichartcategory/).

## ملاحظات

تضيف هذه الطريقة ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [ChartDataWorkbook](../../chartdataworkbook/) لإضافة أو تعديل قيم الخلايا، تأكد من عدم استخدام هذه الورقة. الحد الأقصى لعدد القيم التي تُضاف باستخدام هذه الطريقة لا يجب أن يتجاوز 16711680

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IChartCategory](../../ichartcategory/)
* الفئة [IChartDataCell](../../ichartdatacell/)
* الفئة [ChartCategoryCollection](../)
* الفئة [Object](../../../system/object/)
* النطاق [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)
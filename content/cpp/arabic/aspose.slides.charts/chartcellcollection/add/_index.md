---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: أضف خلية جديدة إلى المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) طريقة

إضافة خلية جديدة إلى المجموعة.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | خلية جديدة للإضافة. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) طريقة

ينشئ [ChartDataCell](../../chartdatacell/) من القيمة المحددة ويضيفه إلى المجموعة.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | القيمة. |

## ملاحظات

هذه الطريقة تضيف ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا كنت تستخدم [ChartDataWorkbook](../../chartdataworkbook/) لإضافة أو تعديل قيم [Cell](../../../aspose.slides/cell/)، تأكد من عدم استخدام ورقة العمل هذه. الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة يجب ألا يتجاوز 16711680

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataCell](../../ichartdatacell/)
* فئة [ChartCellCollection](../)
* فئة [Object](../../../system/object/)
* مساحة اسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)
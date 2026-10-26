---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إضافة خلية جديدة إلى المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) طريقة

أضف خلية جديدة إلى المجموعة.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | خلية جديدة للإضافة. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) طريقة

ينشئ [IChartDataCell](../../ichartdatacell/) من القيمة المحددة ويضيفه إلى المجموعة.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | القيمة. |

## ملاحظات

تضيف هذه الطريقة ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا كنت تستخدم [IChartDataWorkbook](../../ichartdataworkbook/) لإضافة أو تعديل قيم [Cell](../../../aspose.slides/cell/)، تأكد من أنك لا تستخدم هذه الورقة. يجب ألا يتجاوز الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة 16711680

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataCell](../../ichartdatacell/)
* فئة [IChartCellCollection](../)
* فئة [Object](../../../system/object/)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)
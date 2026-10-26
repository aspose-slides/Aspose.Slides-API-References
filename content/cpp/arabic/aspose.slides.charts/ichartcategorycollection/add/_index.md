---
title: Add()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: إذا كانت الفئة موجودة في المجموعة، تُرجعها. وإلا يتم إنشاء فئة مخطط جديدة من IChartDataCell وإضافتها إلى المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) طريقة

إذا كان الفئة موجودة في المجموعة، تُرجعها. وإلا يتم إنشاء فئة مخطط جديدة من [IChartDataCell](../../ichartdatacell/) وإضافتها إلى المجموعة.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) تُستخدم لإنشاء فئة المخطط. |

### قيمة الإرجاع

الفئة المضافة أو الموجودة.

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) طريقة

يُنشئ [IChartCategory](../../ichartcategory/) جديدًا من القيمة ويضيفه إلى المجموعة.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | القيمة. |

### قيمة الإرجاع

تمت إضافة [IChartCategory](../../ichartcategory/).

## ملاحظات

تُضيف هذه الطريقة ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا كنت تستخدم [IChartDataWorkbook](../../ichartdataworkbook/) لإضافة أو تعديل قيم الخلايا، تأكد من أنك لا تستخدم هذه الورقة. يجب ألا يتجاوز الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة 16711680

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
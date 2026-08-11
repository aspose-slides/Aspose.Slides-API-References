---
title: Add()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ سلسلة مخطط جديدة ويضيفها إلى المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) طريقة

ينشئ سلسلة مخطط جديدة ويضيفها إلى المجموعة.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### الوسائط

| معاملة | نوع | الوصف |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | نوع السلسلة |

### قيمة الإرجاع

سلسلة مخطط جديدة.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) طريقة

ينشئ سلسلة مخطط جديدة من [ChartDataCell](../../chartdatacell/) ويضيفها إلى المجموعة.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### الوسائط

| معاملة | نوع | الوصف |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) الذي يحتوي على اسم السلسلة. |
| type | [ChartType](../../charttype/) | نوع مجموعة نوع السلسلة |

### قيمة الإرجاع

تمت إضافة سلسلة المخطط أو السلسلة التي هي بالفعل في المجموعة.

## ملاحظات

إذا كانت سلسلة المخطط تم إنشاؤها من نفس الخلية الموجودة مسبقًا في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد فهرسها.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) طريقة

ينشئ سلسلة مخطط جديدة من [ChartCellCollection](../../chartcellcollection/) ويضيفها إلى المجموعة.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### الوسائط

| معاملة | نوع | الوصف |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | الخلايا التي تحتوي على اسم السلسلة. |
| type | [ChartType](../../charttype/) | نوع مجموعة نوع السلسلة |

### قيمة الإرجاع

تمت إضافة سلسلة المخطط أو السلسلة التي هي بالفعل في المجموعة.

## ملاحظات

إذا كانت سلسلة المخطط تم إنشاؤها من نفس الخلية الموجودة مسبقًا في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد فهرسها.

## ChartSeriesCollection::Add(System::String, ChartType) طريقة

ينشئ سلسلة مخطط جديدة من القيمة ويضيفها إلى المجموعة.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### الوسائط

| معاملة | نوع | الوصف |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | اسم السلسلة. |
| type | [ChartType](../../charttype/) | نوع مجموعة نوع السلسلة |

### قيمة الإرجاع

تمت إضافة سلسلة المخطط.

## أنظر أيضًا

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IChartSeries](../../ichartseries/)
* الفئة [ChartSeriesCollection](../)
* الفئة [IChartDataCell](../../ichartdatacell/)
* الفئة [IChartCellCollection](../../ichartcellcollection/)
* الفئة [String](../../../system/string/)
* النطاق [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)
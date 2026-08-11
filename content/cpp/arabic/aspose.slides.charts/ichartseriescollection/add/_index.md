---
title: Add()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بإنشاء سلسلة مخطط جديدة ويضيفها إلى المجموعة.
type: docs
weight: 14
url: /ar/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) طريقة


يقوم بإنشاء سلسلة مخطط جديدة ويضيفها إلى المجموعة.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | نوع السلسلة |

### قيمة الإرجاع

سلسلة مخطط جديدة.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) طريقة


يقوم بإنشاء سلسلة مخطط جديدة من [IChartDataCell](../../ichartdatacell/) ويضيفها إلى المجموعة.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) التي تحتوي على اسم السلسلة. |
| type | [ChartType](../../charttype/) | نوع مجموعة السلسلة |

### قيمة الإرجاع

السلسلة المضافة أو السلسلة الموجودة بالفعل في المجموعة.

## ملاحظات


إذا تم إنشاء سلسلة مخطط من نفس الخلية الموجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد فهرسها.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) طريقة


يقوم بإنشاء سلسلة مخطط جديدة من [IChartCellCollection](../../ichartcellcollection/) ويضيفها إلى المجموعة.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | الخلايا التي تحتوي على اسم السلسلة. |
| type | [ChartType](../../charttype/) | نوع مجموعة السلسلة |

### قيمة الإرجاع

السلسلة المضافة أو السلسلة الموجودة بالفعل في المجموعة.

## ملاحظات


إذا تم إنشاء سلسلة مخطط من نفس الخلية الموجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد فهرسها.



## IChartSeriesCollection::Add(System::String, ChartType) طريقة


يقوم بإنشاء سلسلة مخطط جديدة من القيمة ويضيفها إلى المجموعة.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | اسم السلسلة. |
| type | [ChartType](../../charttype/) | نوع مجموعة السلسلة |

### قيمة الإرجاع

السلسلة المضافة.



## انظر أيضًا

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
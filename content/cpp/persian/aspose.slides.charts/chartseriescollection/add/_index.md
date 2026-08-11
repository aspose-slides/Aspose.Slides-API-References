---
title: Add()
second_title: Aspose.Slides برای C++ مرجع API
description: یک سری جدید نمودار ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.
type: docs
weight: 53
url: /fa/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) متد


یک سری جدید نمودار ایجاد می‌کند و آن را به مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Type of series |

### مقدار بازگشتی

سری جدید نمودار.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) متد


یک سری جدید نمودار از [ChartDataCell](../../chartdatacell/) ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) که نام سری را شامل می‌شود. |
| type | [ChartType](../../charttype/) | نوع تنظیم شده برای سری |

### مقدار بازگشتی

سری نمودار افزوده‌شده یا سری‌ای که قبلاً در مجموعه وجود داشته است.

## توضیحات

اگر سری نمودار از همان سلول که قبلاً در مجموعه وجود دارد ایجاد شده باشد، متد هیچ چیزی اضافه نمی‌کند و ایندکس آن را برمی‌گرداند.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) متد


یک سری جدید نمودار از [ChartCellCollection](../../chartcellcollection/) ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | سلول‌هایی که نام سری را شامل می‌شوند. |
| type | [ChartType](../../charttype/) | نوع تنظیم شده برای سری |

### مقدار بازگشتی

سری نمودار افزوده‌شده یا سری‌ای که قبلاً در مجموعه وجود داشته است.

## توضیحات

اگر سری نمودار از همان سلول که قبلاً در مجموعه وجود دارد ایجاد شده باشد، متد هیچ چیزی اضافه نمی‌کند و ایندکس آن را برمی‌گرداند.



## ChartSeriesCollection::Add(System::String, ChartType) متد


یک سری جدید نمودار از مقدار ایجاد می‌کند و آن را به مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | نام سری. |
| type | [ChartType](../../charttype/) | نوع تنظیم شده برای سری |

### مقدار بازگشتی

سری نمودار افزوده‌شده.

## مراجع

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartSeries](../../ichartseries/)
* کلاس [ChartSeriesCollection](../)
* کلاس [IChartDataCell](../../ichartdatacell/)
* کلاس [IChartCellCollection](../../ichartcellcollection/)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
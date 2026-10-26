---
title: Add()
second_title: Aspose.Slides برای مرجع API C++
description: یک سری جدید نمودار ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.
type: docs
weight: 14
url: /fa/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) متد

یک سری جدید نمودار ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | نوع سری |

### مقدار بازگشت

سری جدید نمودار.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) متد

یک سری جدید نمودار از [IChartDataCell](../../ichartdatacell/) ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) که شامل نام سری است. |
| type | [ChartType](../../charttype/) | نوع تنظیم شده برای سری |

### مقدار بازگشت

سری نمودار اضافه شده یا سری که قبلاً در مجموعه موجود است.

## یادداشت‌ها

اگر سری نمودار از همان سلول که قبلاً در مجموعه وجود دارد ایجاد شود، متد هیچ چیزی اضافه نمی‌کند و شاخص آن را برمی‌گرداند.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) متد

یک سری جدید نمودار از [IChartCellCollection](../../ichartcellcollection/) ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | سلول‌هایی که شامل نام سری هستند. |
| type | [ChartType](../../charttype/) | نوع تنظیم شده برای سری |

### مقدار بازگشت

سری نمودار اضافه شده یا سری که قبلاً در مجموعه موجود است.

## یادداشت‌ها

اگر سری نمودار از همان سلول که قبلاً در مجموعه وجود دارد ایجاد شود، متد هیچ چیزی اضافه نمی‌کند و شاخص آن را برمی‌گرداند.

## IChartSeriesCollection::Add(System::String, ChartType) متد

یک سری جدید نمودار از مقدار ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | نام سری. |
| type | [ChartType](../../charttype/) | نوع تنظیم شده برای سری |

### مقدار بازگشت

سری نمودار اضافه شده.

## مراجعه

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
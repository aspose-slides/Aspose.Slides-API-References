---
title: IChart
second_title: Aspose.Sildes برای مرجع API .NET
description: نمایش یک نمودار گرافیکی روی یک اسلاید.
type: docs
weight: 1760
url: /fa/aspose.slides.charts/ichart/
---
## رابط IChart

نمایش یک نمودار گرافیکی روی یک اسلاید.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | به دست آوردن رابط پایه IFormattedTextContainer را امکان می‌دهد. فقط-خواندنی [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | به دست آوردن رابط پایه IGraphicalObject را امکان می‌دهد. فقط-خواندنی [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | رابط IOverrideThemeable را برمی‌گرداند. فقط-خواندنی [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | دسترسی به محورهای نمودار را فراهم می‌کند. فقط-خواندنی [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب دیوار پشت یک نمودار 3-بعدی را می‌دهد. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | اطلاعاتی درباره داده‌های پیوندی یا جاسازی‌شده مربوط به یک نمودار را برمی‌گرداند. فقط-خواندنی [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | جدول داده‌های نمودار را برمی‌گرداند. فقط-خواندنی [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | عنوان نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | روش رسم سلول‌های خالی در نمودار را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل-نوشتن [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب کف یک نمودار 3-بعدی را می‌دهد. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | تعیین می‌کند آیا نمودار جدول داده دارد یا خیر. خواندنی/قابل-نوشتن Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | تعیین می‌کند آیا نمودار افسانه (legend) دارد یا خیر. خواندنی/قابل-نوشتن Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | مشخص می‌کند ناحیه نمودار دارای گوشه‌های گرد باشد. خواندنی/قابل-نوشتن Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | تعیین می‌کند آیا عنوان نمودار قابل مشاهده است یا خیر. خواندنی/قابل-نوشتن Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | افسانه (legend) برای نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | نمای ترسیم (plot area) نمودار را نمایان می‌کند. فقط-خواندنی [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | تعیین می‌کند آیا تنها سلول‌های قابل مشاهده رسم شوند. برای رسم هم سلول‌های قابل مشاهده و هم مخفی مقدار False باشد. خواندنی/قابل-نوشتن Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | چرخش 3-بعدی نمودار را برمی‌گرداند. فقط-خواندنی [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | تعیین می‌کند برچسب‌های داده‌ای بیش از حداکثر نمودار نشان داده شوند. خواندنی/قابل-نوشتن Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب دیوار جانبی یک نمودار 3-بعدی را می‌دهد. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | سبک نمودار را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل-نوشتن [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | نوع نمودار را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل-نوشتن [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | اشکالی که در بالای نمودار رسم می‌شوند را مشخص می‌کند. فقط-خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |

## متدها

| Name | Description |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | مقادیر واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### موارد مرتبط

* رابط [IFormattedTextContainer](../iformattedtextcontainer)
* رابط [IGraphicalObject](../../aspose.slides/igraphicalobject)
* رابط [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
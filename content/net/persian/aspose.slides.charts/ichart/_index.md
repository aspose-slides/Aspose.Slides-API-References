---
title: IChart
second_title: Aspose.Sildes برای مرجع API .NET
description: یک نمودار گرافیکی را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 1740
url: /fa/aspose.slides.charts/ichart/
---
## IChart رابط

نمایش یک نمودار گرافیکی بر روی اسلاید.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## خواص

| Name | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | اجازه می‌دهد رابط پایه IFormattedTextContainer را دریافت کند. فقط-خواندنی [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | اجازه می‌دهد رابط پایه IGraphicalObject را دریافت کند. فقط-خواندنی [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | یک رابط IOverrideThemeable را برمی‌گرداند. فقط-خواندنی [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | دسترسی به محورهای نمودار را فراهم می‌کند. فقط-خواندنی [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | یک شیء که امکان تغییر قالب دیوار پشت یک نمودار 3 بعدی را فراهم می‌کند را برمی‌گرداند. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | اطلاعات درباره داده‌های پیوست یا جاسازی‌شده مرتبط با یک نمودار را برمی‌گرداند. فقط-خواندنی [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | یک جدول داده‌ای از یک نمودار را برمی‌گرداند. فقط-خواندنی [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | عنوان نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | نحوه رندر کردن خانه‌های خالی در یک نمودار را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | یک شیء که امکان تغییر قالب کف یک نمودار 3 بعدی را فراهم می‌کند را برمی‌گرداند. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | تعیین می‌کند آیا نمودار جدول داده دارد یا خیر. قابل‌نوشتن Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | تعیین می‌کند آیا نمودار افسانه (legend) دارد یا خیر. قابل‌نوشتن Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | مشخص می‌کند آیا ناحیه نمودار گوشه‌های گرد داشته باشد. قابل‌نوشتن Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | تعیین می‌کند آیا عنوان نمودار قابل مشاهده است یا خیر. قابل‌نوشتن Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | یک افسانه (legend) برای نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | ناحیه رسم نمودار را نمایش می‌دهد. فقط-خواندنی [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | تعیین می‌کند آیا فقط سلول‌های قابل مشاهده رندر شوند. برای رندر هر دو سلول قابل مشاهده و مخفی مقدار False باشد. قابل‌نوشتن Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | یک چرخش 3 بعدی از نمودار را برمی‌گرداند. فقط-خواندنی [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | مشخص می‌کند آیا برچسب‌های داده بر بیشینه نمودار نمایش داده شوند. قابل‌نوشتن Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | یک شیء که امکان تغییر قالب دیوار کناری یک نمودار 3 بعدی را فراهم می‌کند را برمی‌گرداند. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | قالب نمودار را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | نوع نمودار را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | شکل‌های کشیده شده در بالای نمودار را مشخص می‌کند. فقط-خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |

## متدها

| Name | Description |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | مقادیر واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری هستند که رابط IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### مراجع

* رابط [IFormattedTextContainer](../iformattedtextcontainer)
* رابط [IGraphicalObject](../../aspose.slides/igraphicalobject)
* رابط [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
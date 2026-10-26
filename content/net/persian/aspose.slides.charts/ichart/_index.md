---
title: IChart
second_title: مرجع API Aspose.Sildes برای .NET
description: نمودار گرافیکی را بر روی یک اسلاید نمایش می‌دهد.
type: docs
weight: 1740
url: /fa/aspose.slides.charts/ichart/
---
## IChart رابط

Represents an graphic chart on a slide.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | امکان دریافت رابط پایه IFormattedTextContainer را فراهم می‌کند. فقط-خواندنی [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | امکان دریافت رابط پایه IGraphicalObject را فراهم می‌کند. فقط-خواندنی [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | رابط IOverrideThemeable را برمی‌گرداند. فقط-خواندنی [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | دسترسی به محورهای نمودار را فراهم می‌کند. فقط-خواندنی [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | شیئی که امکان تغییر قالب دیوار عقب نمودار ۳-بعدی را فراهم می‌کند را برمی‌گرداند. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | اطلاعات مربوط به داده‌های پیوند داده یا جاسازی‌شده مرتبط با نمودار را برمی‌گرداند. فقط-خواندنی [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | جدول داده‌ای یک نمودار را برمی‌گرداند. فقط-خواندنی [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | عنوان نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | روش رسم سلول‌های خالی در نمودار را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | شیئی که امکان تغییر قالب کف نمودار ۳-بعدی را فراهم می‌کند را برمی‌گرداند. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | مشخص می‌کند که آیا نمودار جدول داده دارد یا خیر. قابل‌خواندن/قابل‌نوشتن بولی. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | مشخص می‌کند که آیا نمودار راهنما دارد یا خیر. قابل‌خواندن/قابل‌نوشتن بولی. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | مشخص می‌کند که ناحیه نمودار دارای گوشه‌های گرد باشد. قابل‌خواندن/قابل‌نوشتن بولی. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | مشخص می‌کند که آیا عنوان نمودار قابل مشاهده است یا خیر. قابل‌خواندن/قابل‌نوشتن بولی. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | راهنمای نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | ناحیه ترسیم نمودار را نشان می‌دهد. فقط-خواندنی [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | مشخص می‌کند که فقط سلول‌های قابل مشاهده رسم شوند. برای رسم هم سلول‌های قابل مشاهده و هم مخفی مقدار False باشد. قابل‌خواندن/قابل‌نوشتن بولی. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | چرخش ۳-بعدی نمودار را برمی‌گرداند. فقط-خواندنی [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | مشخص می‌کند که برچسب‌های داده بر بالای بیشینه نمودار نشان داده شوند. قابل‌خواندن/قابل‌نوشتن بولی. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | شیئی که امکان تغییر قالب دیوار کناری نمودار ۳-بعدی را فراهم می‌کند را برمی‌گرداند. فقط-خواندنی [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | سبک نمودار را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | نوع نمودار را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | اشکال رسم‌شده بر روی نمودار را مشخص می‌کند. فقط-خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |

## متدها

| نام | توضیح |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | مقادیر واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### موارد مرتبط

* رابط [IFormattedTextContainer](../iformattedtextcontainer)
* رابط [IGraphicalObject](../../aspose.slides/igraphicalobject)
* رابط [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
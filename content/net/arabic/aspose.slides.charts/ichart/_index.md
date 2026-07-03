---
title: IChart
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل مخططًا رسوميًا على شريحة.
type: docs
weight: 1740
url: /ar/aspose.slides.charts/ichart/
---
## واجهة IChart

يمثل مخططًا رسوميًا على شريحة.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | يسمح بالحصول على واجهة IFormattedTextContainer الأساسية. للقراءة فقط [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | يسمح بالحصول على واجهة IGraphicalObject الأساسية. للقراءة فقط [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | يرجع واجهة IOverrideThemeable. للقراءة فقط [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | يوفر الوصول إلى محاور المخطط. للقراءة فقط [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | يرجع كائنًا يسمح بتغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. للقراءة فقط [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | يرجع معلومات حول البيانات المرتبطة أو المضمّنة المرتبطة بالمخطط. للقراءة فقط [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | يرجع جدول بيانات للمخطط. للقراءة فقط [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | يرجع أو يعين عنوان المخطط. للقراءة فقط [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | يرجع أو يعين طريقة رسم الخلايا الفارغة في المخطط. قابل للقراءة والكتابة [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | يرجع كائنًا يسمح بتغيير تنسيق أرضية المخطط ثلاثي الأبعاد. للقراءة فقط [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | يحدد ما إذا كان للمخطط جدول بيانات. قابل للقراءة والكتابة Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | يحدد ما إذا كان للمخطط وسيلة إيضاح. قابل للقراءة والكتابة Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | يحدد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. قابل للقراءة والكتابة Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | يحدد ما إذا كان للمخطط عنوان مرئي. قابل للقراءة والكتابة Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | يرجع أو يعين وسيلة إيضاح للمخطط. للقراءة فقط [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | يمثل منطقة الرسم للمخطط. للقراءة فقط [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | يحدد ما إذا تم رسم الخلايا الظاهرة فقط. false لرسم كل من الخلايا الظاهرة والمخفاة. قابل للقراءة والكتابة Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | يرجع دوران ثلاثي الأبعاد للمخطط. للقراءة فقط [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | يحدد ما إذا كانت ملصقات البيانات فوق الحد الأقصى للمخطط يجب أن تُظهر. قابل للقراءة والكتابة Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | يرجع كائنًا يسمح بتغيير تنسيق الجدار الجانبي للمخطط ثلاثي الأبعاد. للقراءة فقط [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | يرجع أو يعين نمط المخطط. قابل للقراءة والكتابة [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | يرجع أو يعين نوع المخطط. قابل للقراءة والكتابة [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | يحدد الأشكال المرسومة فوق المخطط. للقراءة فقط [`IGroupShape`](../../aspose.slides/igroupshape). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | يحسب القيم الفعلية لعناصر المخطط. تشمل القيم الفعلية موضع العناصر التي تنفّذ واجهة IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) والقيم الفعلية للمحاور (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### انظر أيضًا

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
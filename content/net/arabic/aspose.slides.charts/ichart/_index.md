---
title: IChart
second_title: مرجع API Aspose.Sildes لـ .NET
description: يمثل مخططًا رسوميًا على شريحة.
type: docs
weight: 1740
url: /ar/aspose.slides.charts/ichart/
---
## IChart واجهة

يمثل مخططًا رسوميًا على الشريحة.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | يسمح بالحصول على واجهة IFormattedTextContainer الأساسية. للقراءة فقط [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | يسمح بالحصول على واجهة IGraphicalObject الأساسية. للقراءة فقط [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | يرجع واجهة IOverrideThemeable. للقراءة فقط [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | يوفر وصولًا إلى محاور المخطط. للقراءة فقط [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | يرجع كائنًا يتيح تغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. للقراءة فقط [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | يرجع معلومات حول البيانات المرتبطة أو المضمنة المرتبطة بمخطط. للقراءة فقط [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | يرجع جدول بيانات للمخطط. للقراءة فقط [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | يرجع أو يحدد عنوان المخطط. للقراءة فقط [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | يرجع أو يحدد الطريقة لرسم الخلايا الفارغة على المخطط. قراءة/كتابة [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | يرجع كائنًا يتيح تغيير تنسيق أرضية مخطط ثلاثي الأبعاد. للقراءة فقط [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | يحدد ما إذا كان للمخطط جدول بيانات. قراءة/كتابة Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | يحدد ما إذا كان للمخطط وسيلة إيضاح. قراءة/كتابة Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | يحدد أن مساحة المخطط يجب أن تكون ذات زوايا مستديرة. قراءة/كتابة Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | يحدد ما إذا كان للمخطط عنوان مرئي. قراءة/كتابة Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | يرجع أو يحدد وسيلة إيضاح للمخطط. للقراءة فقط [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | يمثل مساحة رسم المخطط. للقراءة فقط [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | يحدد ما إذا كانت الخلايا المرئية فقط هي التي تُرسم. False لرسمة كل من الخلايا المرئية والمخفية. قراءة/كتابة Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | يرجع دورانًا ثلاثيًا الأبعاد للمخطط. للقراءة فقط [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | يحدد أن تُظهر ملصقات البيانات فوق الحد الأقصى للمخطط. قراءة/كتابة Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | يرجع كائنًا يتيح تغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. للقراءة فقط [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | يرجع أو يحدد نمط المخطط. قراءة/كتابة [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | يرجع أو يحدد نوع المخطط. قراءة/كتابة [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | حدد الأشكال المرسومة فوق المخطط. للقراءة فقط [`IGroupShape`](../../aspose.slides/igroupshape). |

## طرق

| الاسم | الوصف |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | يحسّب القيم الفعلية لعناصر المخطط. القيم الفعلية تشمل موضع العناصر التي تنفّذ واجهة IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) وقيم المحاور الفعلية (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### انظر أيضًا

* واجهة [IFormattedTextContainer](../iformattedtextcontainer)
* واجهة [IGraphicalObject](../../aspose.slides/igraphicalobject)
* واجهة [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* مساحة اسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
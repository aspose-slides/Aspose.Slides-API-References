---
title: Chart
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک نمودار گرافیکی را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/chart/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

یک نمودار گرافیکی را بر روی اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | مقادیر واقعی عناصر نمودار را محاسبه می‌کند. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | تعیین می‌کند آیا تنها سلول‌های قابل مشاهده ترسیم می‌شوند. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | تعیین می‌کند آیا تنها سلول‌های قابل مشاهده ترسیم می‌شوند. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | بازمی‌گرداند یا تنظیم می‌کند نحوه ترسیم سلول‌های خالی در یک نمودار. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | بازمی‌گرداند یا تنظیم می‌کند نحوه ترسیم سلول‌های خالی در یک نمودار. |
| [getChartData()](#getChartData--) | بازمی‌گرداند اطلاعات درباره داده‌های پیوندی یا توکار مرتبط با یک نمودار. |
| [hasTitle()](#hasTitle--) | تعیین می‌کند آیا نمودار عنوان قابل مشاهده دارد. |
| [setTitle(boolean value)](#setTitle-boolean-) | تعیین می‌کند آیا نمودار عنوان قابل مشاهده دارد. |
| [getChartTitle()](#getChartTitle--) | بازمی‌گرداند یا تنظیم می‌کند عنوان یک نمودار. |
| [hasDataTable()](#hasDataTable--) | تعیین می‌کند آیا نمودار جدول داده دارد. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | تعیین می‌کند آیا نمودار جدول داده دارد. |
| [hasLegend()](#hasLegend--) | تعیین می‌کند آیا نمودار legend دارد. |
| [setLegend(boolean value)](#setLegend-boolean-) | تعیین می‌کند آیا نمودار legend دارد. |
| [getLegend()](#getLegend--) | بازمی‌گرداند یا تنظیم می‌کند legend برای یک نمودار. |
| [getChartDataTable()](#getChartDataTable--) | بازمی‌گرداند جدول داده‌ای یک نمودار. |
| [getStyle()](#getStyle--) | بازمی‌گرداند یا تنظیم می‌کند سبک نمودار. |
| [setStyle(int value)](#setStyle-int-) | بازمی‌گرداند یا تنظیم می‌کند سبک نمودار. |
| [getType()](#getType--) | بازمی‌گرداند یا تنظیم می‌کند نوع نمودار. |
| [setType(int value)](#setType-int-) | بازمی‌گرداند یا تنظیم می‌کند نوع نمودار. |
| [getPlotArea()](#getPlotArea--) | منطقه رسم یک نمودار را نشان می‌دهد. |
| [getRotation3D()](#getRotation3D--) | بازمی‌گرداند چرخش سه‌بعدی یک نمودار. |
| [getBackWall()](#getBackWall--) | بازمی‌گرداند شیئی که امکان تغییر قالب دیوار پشت یک نمودار سه‌بعدی را فراهم می‌کند. |
| [getSideWall()](#getSideWall--) | بازمی‌گرداند شیئی که امکان تغییر قالب دیوار کناری یک نمودار سه‌بعدی را فراهم می‌کند. |
| [getFloor()](#getFloor--) | بازمی‌گرداند شیئی که امکان تغییر قالب کف یک نمودار سه‌بعدی را فراهم می‌کند. |
| [getTextFormat()](#getTextFormat--) | بازمی‌گرداند قالب متن نمودار. |
| [createThemeEffective()](#createThemeEffective--) | بازمی‌گرداند یک تم مؤثر برای این نمودار. |
| [getThemeManager()](#getThemeManager--) | بازمی‌گرداند مدیر تم. |
| [getUserShapes()](#getUserShapes--) | مشخص می‌کند اشکالی که بر روی نمودار رسم می‌شوند. |
| [getAxes()](#getAxes--) | دسترسی به محورها را فراهم می‌کند. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | مشخص می‌کند برچسب‌های داده فوق حداکثر نمودار نشان داده شوند. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | مشخص می‌کند برچسب‌های داده فوق حداکثر نمودار نشان داده شوند. |
| [hasRoundedCorners()](#hasRoundedCorners--) | مشخص می‌کند ناحیه نمودار گوشه‌های گرد داشته باشد. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | مشخص می‌کند ناحیه نمودار گوشه‌های گرد داشته باشد. |
| [getChart()](#getChart--) |  |
### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

مقادیر واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX، IActualLayout.ActualY، IActualLayout.ActualWidth، IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue، IAxis.ActualMinValue، IAxis.ActualMajorUnit، IAxis.ActualMinorUnit، IAxis.ActualMajorUnitScale، IAxis.ActualMinorUnitScale) است.

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

تعیین می‌کند آیا تنها سلول‌های قابل مشاهده ترسیم می‌شوند. برای ترسیم هر دو سلول قابل مشاهده و مخفی False است. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

تعیین می‌کند آیا تنها سلول‌های قابل مشاهده ترسیم می‌شوند. برای ترسیم هر دو سلول قابل مشاهده و مخفی False است. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

بازمی‌گرداند یا تنظیم می‌کند نحوه ترسیم سلول‌های خالی در یک نمودار. خواندنی/نوشتنی [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**بازمی‌گرداند:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

بازمی‌گرداند یا تنظیم می‌کند نحوه ترسیم سلول‌های خالی در یک نمودار. خواندنی/نوشتنی [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

بازمی‌گرداند اطلاعات درباره داده‌های پیوندی یا توکار مرتبط با یک نمودار. فقط-خواندنی [IChartData](../../com.aspose.slides/ichartdata).

**بازمی‌گرداند:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

تعیین می‌کند آیا نمودار عنوان قابل مشاهده دارد. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

تعیین می‌کند آیا نمودار عنوان قابل مشاهده دارد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

بازمی‌گرداند یا تنظیم می‌کند عنوان یک نمودار. فقط-خواندنی [IChartTitle](../../com.aspose.slides/icharttitle).

**بازمی‌گرداند:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

تعیین می‌کند آیا نمودار جدول داده دارد. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

تعیین می‌کند آیا نمودار جدول داده دارد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

تعیین می‌کند آیا نمودار legend دارد. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

تعیین می‌کند آیا نمودار legend دارد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

بازمی‌گرداند یا تنظیم می‌کند legend برای یک نمودار. فقط-خواندنی [ILegend](../../com.aspose.slides/ilegend).

**بازمی‌گرداند:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

بازمی‌گرداند جدول داده‌ای یک نمودار. فقط-خواندنی [IDataTable](../../com.aspose.slides/idatatable).

**بازمی‌گرداند:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

بازمی‌گرداند یا تنظیم می‌کند سبک نمودار. خواندنی/نوشتنی [StyleType](../../com.aspose.slides/styletype).

**بازمی‌گرداند:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

بازمی‌گرداند یا تنظیم می‌کند سبک نمودار. خواندنی/نوشتنی [StyleType](../../com.aspose.slides/styletype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

بازمی‌گرداند یا تنظیم می‌کند نوع نمودار. خواندنی/نوشتنی [ChartType](../../com.aspose.slides/charttype).

**بازمی‌گرداند:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

بازمی‌گرداند یا تنظیم می‌کند نوع نمودار. خواندنی/نوشتنی [ChartType](../../com.aspose.slides/charttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

منطقه رسم یک نمودار را نشان می‌دهد. فقط-خواندنی [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**بازمی‌گرداند:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

بازمی‌گرداند چرخش سه‌بعدی یک نمودار. فقط-خواندنی [IRotation3D](../../com.aspose.slides/irotation3d).

**بازمی‌گرداند:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

بازمی‌گرداند شیئی که امکان تغییر قالب دیوار پشت یک نمودار سه‌بعدی را فراهم می‌کند. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازمی‌گرداند:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

بازمی‌گرداند شیئی که امکان تغییر قالب دیوار کناری یک نمودار سه‌بعدی را فراهم می‌کند. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازمی‌گرداند:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

بازمی‌گرداند شیئی که امکان تغییر قالب کف یک نمودار سه‌بعدی را فراهم می‌کند. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازمی‌گرداند:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

بازمی‌گرداند قالب متن نمودار. این ویژگی برای انواع زیر قابل اعمال نیست: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). فقط-خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**بازمی‌گرداند:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

بازمی‌گرداند یک تم مؤثر برای این نمودار.

**بازمی‌گرداند:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

بازمی‌گرداند مدیر تم. فقط-خواندنی [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**بازمی‌گرداند:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

مشخص می‌کند اشکالی که بر روی نمودار رسم می‌شوند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

**بازمی‌گرداند:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

دسترسی به محورها را فراهم می‌کند. فقط-خواندنی [IAxesManager](../../com.aspose.slides/iaxesmanager).

**بازمی‌گرداند:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

مشخص می‌کند برچسب‌های داده فوق حداکثر نمودار نشان داده شوند. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

مشخص می‌کند برچسب‌های داده فوق حداکثر نمودار نشان داده شوند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

مشخص می‌کند ناحیه نمودار گوشه‌های گرد داشته باشد. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

مشخص می‌کند ناحیه نمودار گوشه‌های گرد داشته باشد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

بازمی‌گرداند نمودار. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازمی‌گرداند:**
[IChart](../../com.aspose.slides/ichart)
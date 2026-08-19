---
title: IChart
second_title: مرجع API Aspose.Slides برای جاوا
description: یک نمودار گرافیکی را بر روی یک اسلاید نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ichart/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

یک نمودار گرافیکی را بر روی یک اسلاید نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determines whether the only visible cells are plotted. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determines whether the only visible cells are plotted. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Returns or sets the way to plot blank cells on a chart. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Returns or sets the way to plot blank cells on a chart. |
| [getChartData()](#getChartData--) | Returns information about the linked or embedded data associated with a chart. |
| [hasTitle()](#hasTitle--) | Determines whether a chart has a visible title. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determines whether a chart has a visible title. |
| [getChartTitle()](#getChartTitle--) | Returns or sets a chart title Read-only [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Determines whether a chart has a data table. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Determines whether a chart has a data table. |
| [hasLegend()](#hasLegend--) | Determines whether a chart has a legend. |
| [setLegend(boolean value)](#setLegend-boolean-) | Determines whether a chart has a legend. |
| [getLegend()](#getLegend--) | Returns or sets a legend for a chart. |
| [getChartDataTable()](#getChartDataTable--) | Returns a data table of a chart. |
| [getStyle()](#getStyle--) | Returns or sets the chart style. |
| [setStyle(int value)](#setStyle-int-) | Returns or sets the chart style. |
| [getType()](#getType--) | Returns or sets the chart type. |
| [setType(int value)](#setType-int-) | Returns or sets the chart type. |
| [getPlotArea()](#getPlotArea--) | Represents the plot area of a chart. |
| [getRotation3D()](#getRotation3D--) | Returns a 3D rotation of a chart. |
| [getBackWall()](#getBackWall--) | Returns an object which allows to change format of the back wall of a 3D chart. |
| [getSideWall()](#getSideWall--) | Returns an object which allows to change format of the side wall of a 3D chart. |
| [getFloor()](#getFloor--) | Returns an object which allows to change format of the floor of a 3D chart. |
| [getUserShapes()](#getUserShapes--) | Specify the shapes drawn on top of the chart. |
| [getAxes()](#getAxes--) | Provide access to chart axes. |
| [validateChartLayout()](#validateChartLayout--) | Calculates actual values of chart elements. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Specifies data labels over the maximum of the chart shall be shown. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Specifies data labels over the maximum of the chart shall be shown. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Specifies the chart area shall have rounded corners. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Specifies the chart area shall have rounded corners. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

تشخیص می‌دهد که آیا فقط سلول‌های قابل مشاهده ترسیم می‌شوند. برای ترسیم هم سلول‌های قابل مشاهده و هم مخفی مقدار False استفاده می‌شود. boolean خواندنی/نوشتنی.

**باز می‌گرداند:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

تشخیص می‌دهد که آیا فقط سلول‌های قابل مشاهده ترسیم می‌شوند. برای ترسیم هم سلول‌های قابل مشاهده و هم مخفی مقدار False استفاده می‌شود. boolean خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

باز می‌گرداند یا تنظیم می‌کند نحوه ترسیم سلول‌های خالی در یک نمودار. boolean خواندنی/نوشتنی [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**باز می‌گرداند:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

باز می‌گرداند یا تنظیم می‌کند نحوه ترسیم سلول‌های خالی در یک نمودار. int خواندنی/نوشتنی [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

باز می‌گرداند اطلاعات مربوط به داده‌های لینک‌شده یا تعبیه‌شده مرتبط با یک نمودار. فقط-خواندنی [IChartData](../../com.aspose.slides/ichartdata).

**باز می‌گرداند:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

تشخیص می‌دهد که آیا نمودار دارای عنوان قابل مشاهده است. boolean خواندنی/نوشتنی.

**باز می‌گرداند:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

تشخیص می‌دهد که آیا نمودار دارای عنوان قابل مشاهده است. boolean خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

باز می‌گرداند یا تنظیم می‌کند عنوان نمودار فقط-خواندنی [IChartTitle](../../com.aspose.slides/icharttitle).

**باز می‌گرداند:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

تشخیص می‌دهد که آیا نمودار دارای جدول داده است. boolean خواندنی/نوشتنی.

**باز می‌گرداند:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

تشخیص می‌دهد که آیا نمودار دارای جدول داده است. boolean خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

تشخیص می‌دهد که آیا نمودار دارای لِژن(legend) است. boolean خواندنی/نوشتنی.

**باز می‌گرداند:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

تشخیص می‌دهد که آیا نمودار دارای لِژن(legend) است. boolean خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

باز می‌گرداند یا تنظیم می‌کند یک لِژن برای نمودار فقط-خواندنی [ILegend](../../com.aspose.slides/ilegend).

**باز می‌گرداند:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

باز می‌گرداند جدول داده‌ای یک نمودار. فقط-خواندنی [IDataTable](../../com.aspose.slides/idatatable).

**باز می‌گرداند:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

باز می‌گرداند یا تنظیم می‌کند سبک نمودار. int خواندنی/نوشتنی [StyleType](../../com.aspose.slides/styletype).

**باز می‌گرداند:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

باز می‌گرداند یا تنظیم می‌کند سبک نمودار. int خواندنی/نوشتنی [StyleType](../../com.aspose.slides/styletype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

باز می‌گرداند یا تنظیم می‌کند نوع نمودار. int خواندنی/نوشتنی [ChartType](../../com.aspose.slides/charttype).

**باز می‌گرداند:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

باز می‌گرداند یا تنظیم می‌کند نوع نمودار. int خواندنی/نوشتنی [ChartType](../../com.aspose.slides/charttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

نمایش می‌دهد ناحیه ترسیم یک نمودار. فقط-خواندنی [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**باز می‌گرداند:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

باز می‌گرداند چرخش 3بعدی یک نمودار. فقط-خواندنی [IRotation3D](../../com.aspose.slides/irotation3d).

**باز می‌گرداند:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

باز می‌گرداند یک شیء که امکان تغییر فرمت دیوار پشت یک نمودار 3بعدی را می‌دهد. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**باز می‌گرداند:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

باز می‌گرداند یک شیء که امکان تغییر فرمت دیوار کناری یک نمودار 3بعدی را می‌دهد. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**باز می‌گرداند:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

باز می‌گرداند یک شیء که امکان تغییر فرمت کف یک نمودار 3بعدی را می‌دهد. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**باز می‌گرداند:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

مشخص می‌کند اشکالی که بالای نمودار کشیده می‌شوند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

**باز می‌گرداند:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

دسترسی به محورهای نمودار را فراهم می‌کند. فقط-خواندنی [IAxesManager](../../com.aspose.slides/iaxesmanager).

**باز می‌گرداند:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

محاسبه مقادیر واقعی عناصر نمودار. مقادیر واقعی شامل موقعیت عناصری است که اینترفیس IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

مشخص می‌کند برچسب‌های داده بالای حداکثر نمودار نمایش داده شوند. boolean خواندنی/نوشتنی.

**باز می‌گرداند:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

مشخص می‌کند برچسب‌های داده بالای حداکثر نمودار نمایش داده شوند. boolean خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

مشخص می‌کند ناحیه نمودار دارای گوشه‌های گرد باشد. boolean خواندنی/نوشتنی.

**باز می‌گرداند:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

مشخص می‌کند ناحیه نمودار دارای گوشه‌های گرد باشد. boolean خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
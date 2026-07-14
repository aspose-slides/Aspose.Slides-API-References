---
title: IChart
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک نمودار گرافیکی را بر روی اسلایدی نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ichart/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

نمودار گرافیکی را در یک اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده رسم می‌شوند. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده رسم می‌شوند. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | روش رسم سلول‌های خالی در یک نمودار را باز می‌گرداند یا تنظیم می‌کند. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | روش رسم سلول‌های خالی در یک نمودار را باز می‌گرداند یا تنظیم می‌کند. |
| [getChartData()](#getChartData--) | اطلاعات مربوط به داده‌های پیوندخورده یا جاسازی‌شده مرتبط با یک نمودار را باز می‌گرداند. |
| [hasTitle()](#hasTitle--) | تعیین می‌کند که آیا نمودار عنوان قابل مشاهده دارد. |
| [setTitle(boolean value)](#setTitle-boolean-) | تعیین می‌کند که آیا نمودار عنوان قابل مشاهده دارد. |
| [getChartTitle()](#getChartTitle--) | یک عنوان نمودار را باز می‌گرداند یا تنظیم می‌کند فقط-خواندنی [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | تعیین می‌کند که آیا نمودار جدول داده دارد. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | تعیین می‌کند که آیا نمودار جدول داده دارد. |
| [hasLegend()](#hasLegend--) | تعیین می‌کند که آیا نمودار لجند دارد. |
| [setLegend(boolean value)](#setLegend-boolean-) | تعیین می‌کند که آیا نمودار لجند دارد. |
| [getLegend()](#getLegend--) | یک لجند برای نمودار باز می‌گرداند یا تنظیم می‌کند. |
| [getChartDataTable()](#getChartDataTable--) | یک جدول داده از یک نمودار را باز می‌گرداند. |
| [getStyle()](#getStyle--) | قالب نمودار را باز می‌گرداند یا تنظیم می‌کند. |
| [setStyle(int value)](#setStyle-int-) | قالب نمودار را باز می‌گرداند یا تنظیم می‌کند. |
| [getType()](#getType--) | نوع نمودار را باز می‌گرداند یا تنظیم می‌کند. |
| [setType(int value)](#setType-int-) | نوع نمودار را باز می‌گرداند یا تنظیم می‌کند. |
| [getPlotArea()](#getPlotArea--) | منطقه رسم یک نمودار را نشان می‌دهد. |
| [getRotation3D()](#getRotation3D--) | چرخش سه‌بعدی یک نمودار را باز می‌گرداند. |
| [getBackWall()](#getBackWall--) | شیئی را باز می‌گرداند که امکان تغییر قالب دیوار پشتی یک نمودار سه‌بعدی را فراهم می‌کند. |
| [getSideWall()](#getSideWall--) | شیئی را باز می‌گرداند که امکان تغییر قالب دیوار کناری یک نمودار سه‌بعدی را فراهم می‌کند. |
| [getFloor()](#getFloor--) | شیئی را باز می‌گرداند که امکان تغییر قالب کف یک نمودار سه‌بعدی را فراهم می‌کند. |
| [getUserShapes()](#getUserShapes--) | اشکال کشیده شده بر روی نمودار را مشخص می‌کند. |
| [getAxes()](#getAxes--) | دسترسی به محورها (axes) نمودار را فراهم می‌کند. |
| [validateChartLayout()](#validateChartLayout--) | مقادیر واقعی عناصر نمودار را محاسبه می‌کند. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | مشخص می‌کند که برچسب‌های داده بالای حداکثر نمودار نشان داده شوند. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | مشخص می‌کند که برچسب‌های داده بالای حداکثر نمودار نشان داده شوند. |
| [hasRoundedCorners()](#hasRoundedCorners--) | مشخص می‌کند که ناحیه نمودار گوشه‌های گرد داشته باشد. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | مشخص می‌کند که ناحیه نمودار گوشه‌های گرد داشته باشد. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده رسم می‌شوند. برای رسم هم سلول‌های قابل مشاهده و هم مخفی مقدار False باشد. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده رسم می‌شوند. برای رسم هم سلول‌های قابل مشاهده و هم مخفی مقدار False باشد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

روش رسم سلول‌های خالی در یک نمودار را باز می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**بازگشت:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

روش رسم سلول‌های خالی در یک نمودار را باز می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

اطلاعات مربوط به داده‌های پیوندخورده یا جاسازی‌شده مرتبط با یک نمودار را باز می‌گرداند. فقط-خواندنی [IChartData](../../com.aspose.slides/ichartdata).

**بازگشت:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

تعیین می‌کند که آیا نمودار عنوان قابل مشاهده دارد. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

تعیین می‌کند که آیا نمودار عنوان قابل مشاهده دارد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

یک عنوان نمودار را باز می‌گرداند یا تنظیم می‌کند فقط-خواندنی [IChartTitle](../../com.aspose.slides/icharttitle).

**بازگشت:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

تعیین می‌کند که آیا نمودار جدول داده دارد. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

تعیین می‌کند که آیا نمودار جدول داده دارد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

تعیین می‌کند که آیا نمودار لجند دارد. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

تعیین می‌کند که آیا نمودار لجند دارد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

یک لجند برای نمودار باز می‌گرداند یا تنظیم می‌کند فقط-خواندنی [ILegend](../../com.aspose.slides/ilegend).

**بازگشت:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

یک جدول داده از یک نمودار را باز می‌گرداند فقط-خواندنی [IDataTable](../../com.aspose.slides/idatatable).

**بازگشت:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

قالب نمودار را باز می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [StyleType](../../com.aspose.slides/styletype).

**بازگشت:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

قالب نمودار را باز می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [StyleType](../../com.aspose.slides/styletype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

نوع نمودار را باز می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [ChartType](../../com.aspose.slides/charttype).

**بازگشت:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

نوع نمودار را باز می‌گرداند یا تنظیم می‌کند خواندنی/نوشتنی [ChartType](../../com.aspose.slides/charttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

منطقه رسم یک نمودار را نشان می‌دهد فقط-خواندنی [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**بازگشت:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

چرخش سه‌بعدی یک نمودار را باز می‌گرداند فقط-خواندنی [IRotation3D](../../com.aspose.slides/irotation3d).

**بازگشت:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

شیئی را باز می‌گرداند که امکان تغییر قالب دیوار پشتی یک نمودار سه‌بعدی را فراهم می‌کند فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازگشت:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

شیئی را باز می‌گرداند که امکان تغییر قالب دیوار کناری یک نمودار سه‌بعدی را فراهم می‌کند فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازگشت:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

شیئی را باز می‌گرداند که امکان تغییر قالب کف یک نمودار سه‌بعدی را فراهم می‌کند فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازگشت:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

اشکال کشیده شده بر روی نمودار را مشخص می‌کند فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

**بازگشت:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

دسترسی به محورها (axes) نمودار را فراهم می‌کند فقط-خواندنی [IAxesManager](../../com.aspose.slides/iaxesmanager).

**بازگشت:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

محاسبه مقادیر واقعی عناصر نمودار. مقادیر واقعی شامل موقعیت عناصری است که رابط IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

مشخص می‌کند که برچسب‌های داده بالای حداکثر نمودار نشان داده شوند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

مشخص می‌کند که برچسب‌های داده بالای حداکثر نمودار نشان داده شوند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

مشخص می‌کند که ناحیه نمودار گوشه‌های گرد داشته باشد. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

مشخص می‌کند که ناحیه نمودار گوشه‌های گرد داشته باشد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
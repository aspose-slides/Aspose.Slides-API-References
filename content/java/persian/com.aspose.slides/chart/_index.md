---
title: Chart
second_title: مرجع API Aspose.Slides برای Java
description: یک نمودار گرافیکی را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/chart/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)  
```
public class Chart extends GraphicalObject implements IChart
```

نمایش یک نمودار گرافیکی بر روی اسلاید.

## متدها

| متد | توضیح |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | محاسبه مقادیر واقعی عناصر نمودار. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده رسم شوند. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده رسم شوند. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | بازگرداندن یا تنظیم روش رسم سلول‌های خالی روی نمودار. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | بازگرداندن یا تنظیم روش رسم سلول‌های خالی روی نمودار. |
| [getChartData()](#getChartData--) | بازگرداندن اطلاعات درباره داده‌های پیوند خورده یا جاسازی‌شده مرتبط با نمودار. |
| [hasTitle()](#hasTitle--) | تعیین می‌کند که آیا نمودار عنوان قابل مشاهده دارد. |
| [setTitle(boolean value)](#setTitle-boolean-) | تعیین می‌کند که آیا نمودار عنوان قابل مشاهده دارد. |
| [getChartTitle()](#getChartTitle--) | بازگرداندن یا تنظیم عنوان نمودار. |
| [hasDataTable()](#hasDataTable--) | تعیین می‌کند که آیا نمودار جدول داده دارد. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | تعیین می‌کند که آیا نمودار جدول داده دارد. |
| [hasLegend()](#hasLegend--) | تعیین می‌کند که آیا نمودار راهنمایی دارد. |
| [setLegend(boolean value)](#setLegend-boolean-) | تعیین می‌کند که آیا نمودار راهنمایی دارد. |
| [getLegend()](#getLegend--) | بازگرداندن یا تنظیم راهنمایی برای نمودار. |
| [getChartDataTable()](#getChartDataTable--) | بازگرداندن جدول داده‌ای از نمودار. |
| [getStyle()](#getStyle--) | بازگرداندن یا تنظیم سبک نمودار. |
| [setStyle(int value)](#setStyle-int-) | بازگرداندن یا تنظیم سبک نمودار. |
| [getType()](#getType--) | بازگرداندن یا تنظیم نوع نمودار. |
| [setType(int value)](#setType-int-) | بازگرداندن یا تنظیم نوع نمودار. |
| [getPlotArea()](#getPlotArea--) | نمایش ناحیه رسم نمودار. |
| [getRotation3D()](#getRotation3D--) | بازگرداندن چرخش ۳ بعدی نمودار. |
| [getBackWall()](#getBackWall--) | بازگرداندن شیئی که امکان تغییر قالب دیوار پشت نمودار ۳ بعدی را می‌دهد. |
| [getSideWall()](#getSideWall--) | بازگرداندن شیئی که امکان تغییر قالب دیوار کنار نمودار ۳ بعدی را می‌دهد. |
| [getFloor()](#getFloor--) | بازگرداندن شیئی که امکان تغییر قالب کف نمودار ۳ بعدی را می‌دهد. |
| [getTextFormat()](#getTextFormat--) | بازگرداندن قالب متن نمودار. |
| [createThemeEffective()](#createThemeEffective--) | بازگرداندن تم مؤثر برای این نمودار. |
| [getThemeManager()](#getThemeManager--) | بازگرداندن مدیر تم. |
| [getUserShapes()](#getUserShapes--) | مشخص کنید اشکالی که بالای نمودار کشیده می‌شوند. |
| [getAxes()](#getAxes--) | دسترسی به محورهای نمودار را فراهم کنید. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | مشخص می‌کند که برچسب‌های داده بالاتر از حداکثر نمودار نشان داده شوند. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | مشخص می‌کند که برچسب‌های داده بالاتر از حداکثر نمودار نشان داده شوند. |
| [hasRoundedCorners()](#hasRoundedCorners--) | مشخص می‌کند که ناحیه نمودار دارای گوشه‌های گرد باشد. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | مشخص می‌کند که ناحیه نمودار دارای گوشه‌های گرد باشد. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

مقادیر واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط IActualLayout را اجرا می‌کنند (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) و مقادیر واقعی محور‌ها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده رسم شوند. برای رسم هم سلول‌های قابل مشاهده و هم مخفی مقدار False است. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده رسم شوند. برای رسم هم سلول‌های قابل مشاهده و هم مخفی مقدار False است. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

بازگرداندن یا تنظیم روش رسم سلول‌های خالی روی نمودار. خواندنی/قابل نوشتن [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**بازگشت:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

بازگرداندن یا تنظیم روش رسم سلول‌های خالی روی نمودار. خواندنی/قابل نوشتن [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

بازگرداندن اطلاعات درباره داده‌های پیوند خورده یا جاسازی‌شده مرتبط با نمودار. فقط-خواندنی [IChartData](../../com.aspose.slides/ichartdata).

**بازگشت:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

تعیین می‌کند که آیا نمودار عنوان قابل مشاهده دارد. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

تعیین می‌کند که آیا نمودار عنوان قابل مشاهده دارد. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

بازگرداندن یا تنظیم عنوان نمودار. فقط-خواندنی [IChartTitle](../../com.aspose.slides/icharttitle).

**بازگشت:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

تعیین می‌کند که آیا نمودار جدول داده دارد. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

تعیین می‌کند که آیا نمودار جدول داده دارد. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

تعیین می‌کند که آیا نمودار راهنمایی دارد. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

تعیین می‌کند که آیا نمودار راهنمایی دارد. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

بازگرداندن یا تنظیم راهنمایی برای نمودار. فقط-خواندنی [ILegend](../../com.aspose.slides/ilegend).

**بازگشت:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

بازگرداندن جدول داده‌ای از نمودار. فقط-خواندنی [IDataTable](../../com.aspose.slides/idatatable).

**بازگشت:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

بازگرداندن یا تنظیم سبک نمودار. خواندنی/قابل نوشتن [StyleType](../../com.aspose.slides/styletype).

**بازگشت:**  
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

بازگرداندن یا تنظیم سبک نمودار. خواندنی/قابل نوشتن [StyleType](../../com.aspose.slides/styletype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

بازگرداندن یا تنظیم نوع نمودار. خواندنی/قابل نوشتن [ChartType](../../com.aspose.slides/charttype).

**بازگشت:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

بازگرداندن یا تنظیم نوع نمودار. خواندنی/قابل نوشتن [ChartType](../../com.aspose.slides/charttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

نمایش ناحیه رسم نمودار. فقط-خواندنی [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**بازگشت:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

بازگرداندن چرخش ۳ بعدی نمودار. فقط-خواندنی [IRotation3D](../../com.aspose.slides/irotation3d).

**بازگشت:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

بازگرداندن شیئی که امکان تغییر قالب دیوار پشت نمودار ۳ بعدی را می‌دهد. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازگشت:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

بازگرداندن شیئی که امکان تغییر قالب دیوار کنار نمودار ۳ بعدی را می‌دهد. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازگشت:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

بازگرداندن شیئی که امکان تغییر قالب کف نمودار ۳ بعدی را می‌دهد. فقط-خواندنی [IChartWall](../../com.aspose.slides/ichartwall).

**بازگشت:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

بازگرداندن قالب متن نمودار. ویژگی برای انواع زیر قابل اعمال نیست: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). فقط-خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**بازگشت:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

بازگرداندن تم مؤثر برای این نمودار.

**بازگشت:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

بازگرداندن مدیر تم. فقط-خواندنی [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**بازگشت:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

مشخص کنید اشکالی که بالای نمودار کشیده می‌شوند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

**بازگشت:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

دسترسی به محورهای نمودار را فراهم کنید. فقط-خواندنی [IAxesManager](../../com.aspose.slides/iaxesmanager).

**بازگشت:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

مشخص می‌کند که برچسب‌های داده بالاتر از حداکثر نمودار نشان داده شوند. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

مشخص می‌کند که برچسب‌های داده بالاتر از حداکثر نمودار نشان داده شوند. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

مشخص می‌کند که ناحیه نمودار دارای گوشه‌های گرد باشد. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

مشخص می‌کند که ناحیه نمودار دارای گوشه‌های گرد باشد. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

بازگرداندن نمودار. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart)
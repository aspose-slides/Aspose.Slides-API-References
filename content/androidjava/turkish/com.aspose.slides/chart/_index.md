---
title: Chart
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir slaytta grafik bir çizelgeyi temsil eder.
type: docs
url: /tr/com.aspose.slides/chart/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Bir slaytta grafik bir çizelgeyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Çizelge öğelerinin gerçek değerlerini hesaplar. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Yalnızca görünen hücrelerin çizilip çizilmediğini belirler. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Yalnızca görünen hücrelerin çizilip çizilmediğini belirler. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Boş hücrelerin bir çizelgede nasıl çizileceğini getirir ya da ayarlar. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Boş hücrelerin bir çizelgede nasıl çizileceğini getirir ya da ayarlar. |
| [getChartData()](#getChartData--) | Bir çizelgeyle ilişkili bağlı ya da gömülü veri hakkında bilgi getirir. |
| [hasTitle()](#hasTitle--) | Bir çizelgenin görünür bir başlığı olup olmadığını belirler. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bir çizelgenin görünür bir başlığı olup olmadığını belirler. |
| [getChartTitle()](#getChartTitle--) | Bir çizelge başlığını getirir ya da ayarlar. |
| [hasDataTable()](#hasDataTable--) | Bir çizelgenin veri tablosu olup olmadığını belirler. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bir çizelgenin veri tablosu olup olmadığını belirler. |
| [hasLegend()](#hasLegend--) | Bir çizelgenin gösterge tablosu olup olmadığını belirler. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bir çizelgenin gösterge tablosu olup olmadığını belirler. |
| [getLegend()](#getLegend--) | Bir çizelge için gösterge tablosunu getirir ya da ayarlar. |
| [getChartDataTable()](#getChartDataTable--) | Bir çizelgenin veri tablosunu getirir. |
| [getStyle()](#getStyle--) | Çizelge stilini getirir ya da ayarlar. |
| [setStyle(int value)](#setStyle-int-) | Çizelge stilini getirir ya da ayarlar. |
| [getType()](#getType--) | Çizelge tipini getirir ya da ayarlar. |
| [setType(int value)](#setType-int-) | Çizelge tipini getirir ya da ayarlar. |
| [getPlotArea()](#getPlotArea--) | Bir çizelgenin çizim alanını temsil eder. |
| [getRotation3D()](#getRotation3D--) | Bir çizelgenin 3D döndürmesini getirir. |
| [getBackWall()](#getBackWall--) | 3D bir çizelgenin arka duvar formatını değiştirmeye izin veren bir nesneyi getirir. |
| [getSideWall()](#getSideWall--) | 3D bir çizelgenin yan duvar formatını değiştirmeye izin veren bir nesneyi getirir. |
| [getFloor()](#getFloor--) | 3D bir çizelgenin taban formatını değiştirmeye izin veren bir nesneyi getirir. |
| [getTextFormat()](#getTextFormat--) | Çizelge metin formatını getirir. |
| [createThemeEffective()](#createThemeEffective--) | Bu çizelge için etkili bir temayı getirir. |
| [getThemeManager()](#getThemeManager--) | Tema yöneticisini getirir. |
| [getUserShapes()](#getUserShapes--) | Çizelgenin üstüne çizilen şekilleri belirtir. |
| [getAxes()](#getAxes--) | Çizelge eksenlerine erişim sağlar. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Çizelgenin en üstündeki veri etiketlerinin gösterilip gösterilmeyeceğini belirler. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Çizelgenin en üstündeki veri etiketlerinin gösterilip gösterilmeyeceğini belirler. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Çizelge alanının yuvarlak köşelere sahip olacağını belirler. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Çizelge alanının yuvarlak köşelere sahip olacağını belirler. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Çizelge öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, IActualLayout arayüzünü uygulayan öğelerin konumlarını (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir.

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Yalnızca görünen hücrelerin çizilip çizilmediğini belirler. Hem görünen hem gizli hücreleri çizmek için false kullanılır. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Yalnızca görünen hücrelerin çizilip çizilmediğini belirler. Hem görünen hem gizli hücreleri çizmek için false kullanılır. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Bir çizelgede boş hücrelerin nasıl çizileceğini getirir ya da ayarlar. Okunur/Yazılır [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Döndürür:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Bir çizelgede boş hücrelerin nasıl çizileceğini getirir ya da ayarlar. Okunur/Yazılır [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Bir çizelgeyle ilişkili bağlı ya da gömülü veri hakkında bilgi getirir. Salt-okunur [IChartData](../../com.aspose.slides/ichartdata).

**Döndürür:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Bir çizelgenin görünür bir başlığı olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Bir çizelgenin görünür bir başlığı olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Bir çizelge başlığını getirir ya da ayarlar. Salt-okunur [IChartTitle](../../com.aspose.slides/icharttitle).

**Döndürür:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Bir çizelgenin veri tablosu olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Bir çizelgenin veri tablosu olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Bir çizelgenin gösterge tablosu olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Bir çizelgenin gösterge tablosu olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Bir çizelge için gösterge tablosunu getirir ya da ayarlar. Salt-okunur [ILegend](../../com.aspose.slides/ilegend).

**Döndürür:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Bir çizelgenin veri tablosunu getirir. Salt-okunur [IDataTable](../../com.aspose.slides/idatatable).

**Döndürür:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

Çizelge stilini getirir ya da ayarlar. Okunur/Yazılır [StyleType](../../com.aspose.slides/styletype).

**Döndürür:**
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Çizelge stilini getirir ya da ayarlar. Okunur/Yazılır [StyleType](../../com.aspose.slides/styletype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Çizelge tipini getirir ya da ayarlar. Okunur/Yazılır [ChartType](../../com.aspose.slides/charttype).

**Döndürür:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Çizelge tipini getirir ya da ayarlar. Okunur/Yazılır [ChartType](../../com.aspose.slides/charttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Bir çizelgenin çizim alanını temsil eder. Salt-okunur [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Döndürür:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Bir çizelgenin 3D döndürmesini getirir. Salt-okunur [IRotation3D](../../com.aspose.slides/irotation3d).

**Döndürür:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

3D bir çizelgenin arka duvar formatını değiştirmeye izin veren bir nesneyi getirir. Salt-okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

3D bir çizelgenin yan duvar formatını değiştirmeye izin veren bir nesneyi getirir. Salt-okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

3D bir çizelgenin taban formatını değiştirmeye izin veren bir nesneyi getirir. Salt-okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Çizelge metin formatını getirir. Özellik aşağıdaki tipler için geçerli değildir: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Salt-okunur [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Döndürür:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Bu çizelge için etkili bir temayı getirir.

**Döndürür:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Tema yöneticisini getirir. Salt-okunur [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Döndürür:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Çizelgenin üstüne çizilen şekilleri belirtir. Salt-okunur [IGroupShape](../../com.aspose.slides/igroupshape).

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Çizelge eksenlerine erişim sağlar. Salt-okunur [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Döndürür:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Çizelgenin en üstündeki veri etiketlerinin gösterilip gösterilmeyeceğini belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Çizelgenin en üstündeki veri etiketlerinin gösterilip gösterilmeyeceğini belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Çizelge alanının yuvarlak köşelere sahip olacağını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Çizelge alanının yuvarlak köşelere sahip olacağını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Çizelgeyi getirir. Salt-okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)
---
title: Chart
second_title: Aspose.Slides Java API Referansı
description: Bir slayttaki grafik çizelgeyi temsil eder.
type: docs
url: /tr/com.aspose.slides/chart/
---
**Kalıtım:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tüm Uygulanan Arabirimler:**  
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)  
```
public class Chart extends GraphicalObject implements IChart
```

Bir slayt üzerindeki grafik çizelgeyi temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Çizelge öğelerinin gerçek değerlerini hesaplar. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Yalnızca görünen hücrelerin çizilip çizilmediğini belirler. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Yalnızca görünen hücrelerin çizilip çizilmediğini belirler. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Boş hücrelerin bir çizelgede nasıl çizileceğini alır veya ayarlar. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Boş hücrelerin bir çizelgede nasıl çizileceğini alır veya ayarlar. |
| [getChartData()](#getChartData--) | Bir çizelgeyle ilişkili bağlantılı veya gömülü veri hakkında bilgi verir. |
| [hasTitle()](#hasTitle--) | Bir çizelgenin görünen bir başlığı olup olmadığını belirler. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bir çizelgenin görünen bir başlığı olup olmadığını belirler. |
| [getChartTitle()](#getChartTitle--) | Bir çizelge başlığını alır veya ayarlar. |
| [hasDataTable()](#hasDataTable--) | Bir çizelgenin veri tablosu içerip içermediğini belirler. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bir çizelgenin veri tablosu içerip içermediğini belirler. |
| [hasLegend()](#hasLegend--) | Bir çizelgenin gösterge (legend) içerip içermediğini belirler. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bir çizelgenin gösterge (legend) içerip içermediğini belirler. |
| [getLegend()](#getLegend--) | Bir çizelge için göstergeyi alır veya ayarlar. |
| [getChartDataTable()](#getChartDataTable--) | Bir çizelgenin veri tablosunu alır. |
| [getStyle()](#getStyle--) | Çizelge stilini alır veya ayarlar. |
| [setStyle(int value)](#setStyle-int-) | Çizelge stilini alır veya ayarlar. |
| [getType()](#getType--) | Çizelge tipini alır veya ayarlar. |
| [setType(int value)](#setType-int-) | Çizelge tipini alır veya ayarlar. |
| [getPlotArea()](#getPlotArea--) | Bir çizelgenin çizim alanını temsil eder. |
| [getRotation3D()](#getRotation3D--) | Bir çizelgenin 3D dönüşünü alır. |
| [getBackWall()](#getBackWall--) | 3D bir çizelgenin arka duvar formatını değiştirmeye izin veren nesneyi alır. |
| [getSideWall()](#getSideWall--) | 3D bir çizelgenin yan duvar formatını değiştirmeye izin veren nesneyi alır. |
| [getFloor()](#getFloor--) | 3D bir çizelgenin taban formatını değiştirmeye izin veren nesneyi alır. |
| [getTextFormat()](#getTextFormat--) | Çizelge metin formatını alır. |
| [createThemeEffective()](#createThemeEffective--) | Bu çizelge için etkili bir temayı alır. |
| [getThemeManager()](#getThemeManager--) | Tema yöneticisini alır. |
| [getUserShapes()](#getUserShapes--) | Çizelgenin üstünde çizilen şekilleri belirtir. |
| [getAxes()](#getAxes--) | Çizelge eksenlerine erişim sağlar. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Çizelge üzerindeki maksimum değerin üstünde veri etiketlerinin gösterilip gösterilmeyeceğini belirler. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Çizelge üzerindeki maksimum değerin üstünde veri etiketlerinin gösterilip gösterilmeyeceğini belirler. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Çizelge alanının yuvarlatılmış köşelere sahip olmasını belirtir. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Çizelge alanının yuvarlatılmış köşelere sahip olmasını belirtir. |
| [getChart()](#getChart--) |  |
### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Çizelge öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, IActualLayout arayüzünü (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) uygulayan öğelerin konumlarını ve eksenlerin gerçek değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir.

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Yalnızca görünen hücrelerin çizilip çizilmediğini belirler. Her iki görünür ve gizli hücreyi çizmek için False. Okunur/Yazılır boolean.

**Döndürür:**  
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Yalnızca görünen hücrelerin çizilip çizilmediğini belirler. Her iki görünür ve gizli hücreyi çizmek için False. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Boş hücrelerin bir çizelgede nasıl çizileceğini alır veya ayarlar. Okunur/Yazılır [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Döndürür:**  
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Boş hücrelerin bir çizelgede nasıl çizileceğini alır veya ayarlar. Okunur/Yazılır [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Bir çizelgeyle ilişkili bağlantılı veya gömülü veri hakkında bilgi verir. Sadece okuma [IChartData](../../com.aspose.slides/ichartdata).

**Döndürür:**  
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Bir çizelgenin görünen bir başlığı olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**  
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Bir çizelgenin görünen bir başlığı olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Bir çizelge başlığını alır veya ayarlar. Sadece okuma [IChartTitle](../../com.aspose.slides/icharttitle).

**Döndürür:**  
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Bir çizelgenin veri tablosu içerip içermediğini belirler. Okunur/Yazılır boolean.

**Döndürür:**  
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Bir çizelgenin veri tablosu içerip içermediğini belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Bir çizelgenin gösterge (legend) içerip içermediğini belirler. Okunur/Yazılır boolean.

**Döndürür:**  
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Bir çizelgenin gösterge (legend) içerip içermediğini belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Bir çizelge için göstergeyi alır veya ayarlar. Sadece okuma [ILegend](../../com.aspose.slides/ilegend).

**Döndürür:**  
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Bir çizelgenin veri tablosunu alır. Sadece okuma [IDataTable](../../com.aspose.slides/idatatable).

**Döndürür:**  
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Çizelge stilini alır veya ayarlar. Okunur/Yazılır [StyleType](../../com.aspose.slides/styletype).

**Döndürür:**  
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Çizelge stilini alır veya ayarlar. Okunur/Yazılır [StyleType](../../com.aspose.slides/styletype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Çizelge tipini alır veya ayarlar. Okunur/Yazılır [ChartType](../../com.aspose.slides/charttype).

**Döndürür:**  
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Çizelge tipini alır veya ayarlar. Okunur/Yazılır [ChartType](../../com.aspose.slides/charttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Bir çizelgenin çizim alanını temsil eder. Sadece okuma [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Döndürür:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Bir çizelgenin 3D dönüşünü alır. Sadece okuma [IRotation3D](../../com.aspose.slides/irotation3d).

**Döndürür:**  
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

3D bir çizelgenin arka duvar formatını değiştirmeye izin veren nesneyi alır. Sadece okuma [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**  
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

3D bir çizelgenin yan duvar formatını değiştirmeye izin veren nesneyi alır. Sadece okuma [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**  
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

3D bir çizelgenin taban formatını değiştirmeye izin veren nesneyi alır. Sadece okuma [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**  
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Çizelge metin formatını alır. Özellik aşağıdaki türler için geçerli değildir: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Sadece okuma [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Döndürür:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Bu çizelge için etkili bir tema döndürür.

**Döndürür:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Tema yöneticisini alır. Sadece okuma [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Döndürür:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Çizelgenin üstünde çizilen şekilleri belirtir. Sadece okuma [IGroupShape](../../com.aspose.slides/igroupshape).

**Döndürür:**  
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Çizelge eksenlerine erişim sağlar. Sadece okuma [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Döndürür:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Çizelge üzerindeki maksimum değerin üstünde veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılır boolean.

**Döndürür:**  
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Çizelge üzerindeki maksimum değerin üstünde veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Çizelge alanının yuvarlatılmış köşelere sahip olmasını belirtir. Okunur/Yazılır boolean.

**Döndürür:**  
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Çizelge alanının yuvarlatılmış köşelere sahip olmasını belirtir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Çizelgeyi alır. Sadece okuma [IChart](../../com.aspose.slides/ichart).

**Döndürür:**  
[IChart](../../com.aspose.slides/ichart)
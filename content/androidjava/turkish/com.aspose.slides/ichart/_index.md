---
title: IChart
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir slaytta grafik çizelgeyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ichart/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Bir slayttaki grafik çizelgesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Sadece görünen hücrelerin çizilip çizilmediğini belirler. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Sadece görünen hücrelerin çizilip çizilmediğini belirler. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Boş hücrelerin bir çizelgede nasıl çizileceğini döndürür ya da ayarlar. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Boş hücrelerin bir çizelgede nasıl çizileceğini döndürür ya da ayarlar. |
| [getChartData()](#getChartData--) | Bir çizelgeye bağlı veya gömülü veri hakkında bilgi getirir. |
| [hasTitle()](#hasTitle--) | Bir çizelgenin görünür başlığı olup olmadığını belirler. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bir çizelgenin görünür başlığı olup olmadığını belirler. |
| [getChartTitle()](#getChartTitle--) | Bir çizelge başlığını döndürür ya da ayarlar Sadece okunur [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Bir çizelgenin veri tablosuna sahip olup olmadığını belirler. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bir çizelgenin veri tablosuna sahip olup olmadığını belirler. |
| [hasLegend()](#hasLegend--) | Bir çizelgenin legend'ı olup olmadığını belirler. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bir çizelgenin legend'ı olup olmadığını belirler. |
| [getLegend()](#getLegend--) | Bir çizelge için legend'ı döndürür ya da ayarlar. |
| [getChartDataTable()](#getChartDataTable--) | Bir çizelgenin veri tablosunu getirir. |
| [getStyle()](#getStyle--) | Çizelge stilini döndürür ya da ayarlar. |
| [setStyle(int value)](#setStyle-int-) | Çizelge stilini döndürür ya da ayarlar. |
| [getType()](#getType--) | Çizelge tipini döndürür ya da ayarlar. |
| [setType(int value)](#setType-int-) | Çizelge tipini döndürür ya da ayarlar. |
| [getPlotArea()](#getPlotArea--) | Bir çizelgenin çizim alanını temsil eder. |
| [getRotation3D()](#getRotation3D--) | Bir çizelgenin 3B dönüşünü getirir. |
| [getBackWall()](#getBackWall--) | Bir 3B çizelgenin arka duvar formatını değiştirmeye izin veren bir nesneyi döndürür. |
| [getSideWall()](#getSideWall--) | Bir 3B çizelgenin yan duvar formatını değiştirmeye izin veren bir nesneyi döndürür. |
| [getFloor()](#getFloor--) | Bir 3B çizelgenin taban formatını değiştirmeye izin veren bir nesneyi döndürür. |
| [getUserShapes()](#getUserShapes--) | Çizelge üzerinde çizilen şekilleri belirtir. |
| [getAxes()](#getAxes--) | Çizelge eksenlerine erişim sağlar. |
| [validateChartLayout()](#validateChartLayout--) | Çizelge öğelerinin gerçek değerlerini hesaplar. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Çizelgenin maksimumu üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Çizelgenin maksimumu üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Çizelge alanının yuvarlatılmış köşelere sahip olacağını belirtir. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Çizelge alanının yuvarlatılmış köşelere sahip olacağını belirtir. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Sadece görünen hücrelerin çizilip çizilmediğini belirler. Hem görünen hem de gizli hücreleri çizmek için false. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Sadece görünen hücrelerin çizilip çizilmediğini belirler. Hem görünen hem de gizli hücreleri çizmek için false. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Boş hücrelerin bir çizelgede nasıl çizileceğini döndürür ya da ayarlar. Okunur/Yazılır [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Döndürür:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Boş hücrelerin bir çizelgede nasıl çizileceğini döndürür ya da ayarlar. Okunur/Yazılır [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Bir çizelgeye bağlı veya gömülü veri hakkında bilgi döndürür. Sadece okunur [IChartData](../../com.aspose.slides/ichartdata).

**Döndürür:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bir çizelgenin görünür başlığı olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bir çizelgenin görünür başlığı olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Bir çizelge başlığını döndürür ya da ayarlar Sadece okunur [IChartTitle](../../com.aspose.slides/icharttitle).

**Döndürür:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Bir çizelgenin veri tablosuna sahip olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Bir çizelgenin veri tablosuna sahip olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Bir çizelgenin legend'ı olup olmadığını belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Bir çizelgenin legend'ı olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Bir çizelge için legend'ı döndürür ya da ayarlar. Sadece okunur [ILegend](../../com.aspose.slides/ilegend).

**Döndürür:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Bir çizelgenin veri tablosunu döndürür. Sadece okunur [IDataTable](../../com.aspose.slides/idatatable).

**Döndürür:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Çizelge stilini döndürür ya da ayarlar. Okunur/Yazılır [StyleType](../../com.aspose.slides/styletype).

**Döndürür:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Çizelge stilini döndürür ya da ayarlar. Okunur/Yazılır [StyleType](../../com.aspose.slides/styletype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Çizelge tipini döndürür ya da ayarlar. Okunur/Yazılır [ChartType](../../com.aspose.slides/charttype).

**Döndürür:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Çizelge tipini döndürür ya da ayarlar. Okunur/Yazılır [ChartType](../../com.aspose.slides/charttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Bir çizelgenin çizim alanını temsil eder. Sadece okunur [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Döndürür:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Bir çizelgenin 3B dönüşünü döndürür. Sadece okunur [IRotation3D](../../com.aspose.slides/irotation3d).

**Döndürür:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Bir 3B çizelgenin arka duvar formatını değiştirmeye izin veren bir nesneyi döndürür. Sadece okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Bir 3B çizelgenin yan duvar formatını değiştirmeye izin veren bir nesneyi döndürür. Sadece okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Bir 3B çizelgenin taban formatını değiştirmeye izin veren bir nesneyi döndürür. Sadece okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Çizelge üzerinde çizilen şekilleri belirtir. Sadece okunur [IGroupShape](../../com.aspose.slides/igroupshape).

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Çizelge eksenlerine erişim sağlar. Sadece okunur [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Döndürür:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Çizelge öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, IActualLayout arayüzünü uygulayan öğelerin konumunu (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir.

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Çizelgenin maksimumu üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Çizelgenin maksimumu üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Çizelge alanının yuvarlatılmış köşelere sahip olacağını belirtir. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Çizelge alanının yuvarlatılmış köşelere sahip olacağını belirtir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
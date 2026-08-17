---
title: IChart
second_title: Aspose.Slides için Java API Referansı
description: Bir slayttaki grafik tabloyu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichart/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Bir slaytta grafik grafiğini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Sadece görünen hücrelerin çizilip çizilmediğini belirler. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Sadece görünen hücrelerin çizilip çizilmediğini belirler. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Bir grafikte boş hücrelerin nasıl çizileceğini alır veya ayarlar. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Bir grafikte boş hücrelerin nasıl çizileceğini alır veya ayarlar. |
| [getChartData()](#getChartData--) | Bir grafiğe bağlı veya gömülü veriler hakkında bilgi alır. |
| [hasTitle()](#hasTitle--) | Bir grafiğin görünür bir başlığı olup olmadığını belirler. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bir grafiğin görünür bir başlığı olup olmadığını belirler. |
| [getChartTitle()](#getChartTitle--) | Bir grafik başlığını alır veya ayarlar Salt okunur [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Bir grafiğin veri tablosuna sahip olup olmadığını belirler. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bir grafiğin veri tablosuna sahip olup olmadığını belirler. |
| [hasLegend()](#hasLegend--) | Bir grafiğin bir gösterge çizgisine sahip olup olmadığını belirler. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bir grafiğin bir gösterge çizgisine sahip olup olmadığını belirler. |
| [getLegend()](#getLegend--) | Bir grafik için bir gösterge çizgisini alır veya ayarlar. |
| [getChartDataTable()](#getChartDataTable--) | Bir grafiğin veri tablosunu alır. |
| [getStyle()](#getStyle--) | Grafik stilini alır veya ayarlar. |
| [setStyle(int value)](#setStyle-int-) | Grafik stilini alır veya ayarlar. |
| [getType()](#getType--) | Grafik tipini alır veya ayarlar. |
| [setType(int value)](#setType-int-) | Grafik tipini alır veya ayarlar. |
| [getPlotArea()](#getPlotArea--) | Bir grafiğin çizim alanını temsil eder. |
| [getRotation3D()](#getRotation3D--) | Bir grafiğin 3B dönüşünü alır. |
| [getBackWall()](#getBackWall--) | 3B bir grafiğin arka duvarının biçimini değiştirmeye izin veren bir nesne döndürür. |
| [getSideWall()](#getSideWall--) | 3B bir grafiğin yan duvarının biçimini değiştirmeye izin veren bir nesne döndürür. |
| [getFloor()](#getFloor--) | 3B bir grafiğin tabanının biçimini değiştirmeye izin veren bir nesne döndürür. |
| [getUserShapes()](#getUserShapes--) | Grafiğin üstüne çizilen şekilleri belirtir. |
| [getAxes()](#getAxes--) | Grafik eksenlerine erişim sağlar. |
| [validateChartLayout()](#validateChartLayout--) | Grafik öğelerinin gerçek değerlerini hesaplar. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Grafiğin maksimum değerinin üzerindeki veri etiketlerinin gösterilmesini belirtir. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Grafiğin maksimum değerinin üzerindeki veri etiketlerinin gösterilmesini belirtir. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Grafik alanının yuvarlatılmış köşelere sahip olmasını belirtir. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Grafik alanının yuvarlatılmış köşelere sahip olmasını belirtir. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```


Sadece görünen hücrelerin çizilip çizilmediğini belirler. Görünür ve gizli hücrelerin ikisini de çizmek için False. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```


Sadece görünen hücrelerin çizilip çizilmediğini belirler. Görünür ve gizli hücrelerin ikisini de çizmek için False. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```


Bir grafikte boş hücrelerin nasıl çizileceğini alır veya ayarlar Okuma/Yazma [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Döndürür:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```


Bir grafikte boş hücrelerin nasıl çizileceğini alır veya ayarlar Okuma/Yazma [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```


Bir grafiğe bağlı veya gömülü veriler hakkında bilgi alır. Salt okunur [IChartData](../../com.aspose.slides/ichartdata).

**Döndürür:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```


Bir grafiğin görünür bir başlığı olup olmadığını belirler. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```


Bir grafiğin görünür bir başlığı olup olmadığını belirler. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```


Bir grafik başlığını alır veya ayarlar Salt okunur [IChartTitle](../../com.aspose.slides/icharttitle).

**Döndürür:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```


Bir grafiğin veri tablosuna sahip olup olmadığını belirler. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```


Bir grafiğin veri tablosuna sahip olup olmadığını belirler. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```


Bir grafiğin bir gösterge çizgisine sahip olup olmadığını belirler. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```


Bir grafiğin bir gösterge çizgisine sahip olup olmadığını belirler. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```


Bir grafik için bir gösterge çizgisini alır veya ayarlar Salt okunur [ILegend](../../com.aspose.slides/ilegend).

**Döndürür:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```


Bir grafiğin veri tablosunu alır. Salt okunur [IDataTable](../../com.aspose.slides/idatatable).

**Döndürür:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```


Grafik stilini alır veya ayarlar Okuma/Yazma [StyleType](../../com.aspose.slides/styletype).

**Döndürür:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```


Grafik stilini alır veya ayarlar Okuma/Yazma [StyleType](../../com.aspose.slides/styletype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```


Grafik tipini alır veya ayarlar Okuma/Yazma [ChartType](../../com.aspose.slides/charttype).

**Döndürür:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Grafik tipini alır veya ayarlar Okuma/Yazma [ChartType](../../com.aspose.slides/charttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```


Bir grafiğin çizim alanını temsil eder. Salt okunur [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Döndürür:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```


Bir grafiğin 3B dönüşünü alır. Salt okunur [IRotation3D](../../com.aspose.slides/irotation3d).

**Döndürür:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```


3B bir grafiğin arka duvarının biçimini değiştirmeye izin veren bir nesne döndürür. Salt okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```


3B bir grafiğin yan duvarının biçimini değiştirmeye izin veren bir nesne döndürür. Salt okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```


3B bir grafiğin tabanının biçimini değiştirmeye izin veren bir nesne döndürür. Salt okunur [IChartWall](../../com.aspose.slides/ichartwall).

**Döndürür:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```


Grafiğin üstüne çizilen şekilleri belirtir. Salt okunur [IGroupShape](../../com.aspose.slides/igroupshape).

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```


Grafik eksenlerine erişim sağlar. Salt okunur [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Döndürür:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```


Grafik öğelerinin gerçek değerlerini hesaplar. Gerçek değerler IActualLayout arayüzünü uygulayan öğelerin konumlarını (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir.
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```


Grafiğin maksimum değerinin üzerindeki veri etiketlerinin gösterilmesini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```


Grafiğin maksimum değerinin üzerindeki veri etiketlerinin gösterilmesini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```


Grafik alanının yuvarlatılmış köşelere sahip olmasını belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```


Grafik alanının yuvarlatılmış köşelere sahip olmasını belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
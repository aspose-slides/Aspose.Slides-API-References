---
title: Chart
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili bagan grafis pada slide.
type: docs
url: /id/com.aspose.slides/chart/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Mewakili bagan grafis pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Menghitung nilai aktual elemen bagan. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Menentukan apakah hanya sel yang terlihat yang dipetakan. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Menentukan apakah hanya sel yang terlihat yang dipetakan. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Mengembalikan atau mengatur cara memetakan sel kosong pada bagan. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Mengembalikan atau mengatur cara memetakan sel kosong pada bagan. |
| [getChartData()](#getChartData--) | Mengembalikan informasi tentang data yang ditautkan atau disematkan yang terkait dengan bagan. |
| [hasTitle()](#hasTitle--) | Menentukan apakah bagan memiliki judul yang terlihat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Menentukan apakah bagan memiliki judul yang terlihat. |
| [getChartTitle()](#getChartTitle--) | Mengembalikan atau mengatur judul bagan. |
| [hasDataTable()](#hasDataTable--) | Menentukan apakah bagan memiliki tabel data. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Menentukan apakah bagan memiliki tabel data. |
| [hasLegend()](#hasLegend--) | Menentukan apakah bagan memiliki legenda. |
| [setLegend(boolean value)](#setLegend-boolean-) | Menentukan apakah bagan memiliki legenda. |
| [getLegend()](#getLegend--) | Mengembalikan atau mengatur legenda untuk bagan. |
| [getChartDataTable()](#getChartDataTable--) | Mengembalikan tabel data bagan. |
| [getStyle()](#getStyle--) | Mengembalikan atau mengatur gaya bagan. |
| [setStyle(int value)](#setStyle-int-) | Mengembalikan atau mengatur gaya bagan. |
| [getType()](#getType--) | Mengembalikan atau mengatur jenis bagan. |
| [setType(int value)](#setType-int-) | Mengembalikan atau mengatur jenis bagan. |
| [getPlotArea()](#getPlotArea--) | Mewakili area plot bagan. |
| [getRotation3D()](#getRotation3D--) | Mengembalikan rotasi 3D bagan. |
| [getBackWall()](#getBackWall--) | Mengembalikan objek yang memungkinkan mengubah format dinding belakang bagan 3D. |
| [getSideWall()](#getSideWall--) | Mengembalikan objek yang memungkinkan mengubah format dinding sisi bagan 3D. |
| [getFloor()](#getFloor--) | Mengembalikan objek yang memungkinkan mengubah format lantai bagan 3D. |
| [getTextFormat()](#getTextFormat--) | Mengembalikan format teks bagan. |
| [createThemeEffective()](#createThemeEffective--) | Mengembalikan tema efektif untuk bagan ini. |
| [getThemeManager()](#getThemeManager--) | Mengembalikan pengelola tema. |
| [getUserShapes()](#getUserShapes--) | Menentukan bentuk yang digambar di atas bagan. |
| [getAxes()](#getAxes--) | Menyediakan akses ke sumbu bagan. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Menentukan label data di atas maksimum bagan akan ditampilkan. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Menentukan label data di atas maksimum bagan akan ditampilkan. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Menentukan area bagan memiliki sudut melengkung. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Menentukan area bagan memiliki sudut melengkung. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Menghitung nilai aktual elemen bagan. Nilai aktual mencakup posisi elemen yang mengimplementasikan antarmuka IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) dan nilai sumbu aktual (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Menentukan apakah hanya sel yang terlihat yang dipetakan. False untuk memetakan sel yang terlihat dan tersembunyi. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Menentukan apakah hanya sel yang terlihat yang dipetakan. False untuk memetakan sel yang terlihat dan tersembunyi. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Mengembalikan atau mengatur cara memetakan sel kosong pada bagan. Baca/tulis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Mengembalikan:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Mengembalikan atau mengatur cara memetakan sel kosong pada bagan. Baca/tulis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Mengembalikan informasi tentang data yang ditautkan atau disematkan yang terkait dengan bagan. Baca-saja [IChartData](../../com.aspose.slides/ichartdata).

**Mengembalikan:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Menentukan apakah bagan memiliki judul yang terlihat. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Menentukan apakah bagan memiliki judul yang terlihat. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Mengembalikan atau mengatur judul bagan. Baca-saja [IChartTitle](../../com.aspose.slides/icharttitle).

**Mengembalikan:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Menentukan apakah bagan memiliki tabel data. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Menentukan apakah bagan memiliki tabel data. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Menentukan apakah bagan memiliki legenda. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Menentukan apakah bagan memiliki legenda. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Mengembalikan atau mengatur legenda untuk bagan. Baca-saja [ILegend](../../com.aspose.slides/ilegend).

**Mengembalikan:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Mengembalikan tabel data bagan. Baca-saja [IDataTable](../../com.aspose.slides/idatatable).

**Mengembalikan:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Mengembalikan atau mengatur gaya bagan. Baca/tulis [StyleType](../../com.aspose.slides/styletype).

**Mengembalikan:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Mengembalikan atau mengatur gaya bagan. Baca/tulis [StyleType](../../com.aspose.slides/styletype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Mengembalikan atau mengatur jenis bagan. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Mengembalikan:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Mengembalikan atau mengatur jenis bagan. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Mewakili area plot bagan. Baca-saja [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Mengembalikan:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Mengembalikan rotasi 3D bagan. Baca-saja [IRotation3D](../../com.aspose.slides/irotation3d).

**Mengembalikan:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Mengembalikan objek yang memungkinkan mengubah format dinding belakang bagan 3D. Baca-saja [IChartWall](../../com.aspose.slides/ichartwall).

**Mengembalikan:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Mengembalikan objek yang memungkinkan mengubah format dinding sisi bagan 3D. Baca-saja [IChartWall](../../com.aspose.slides/ichartwall).

**Mengembalikan:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Mengembalikan objek yang memungkinkan mengubah format lantai bagan 3D. Baca-saja [IChartWall](../../com.aspose.slides/ichartwall).

**Mengembalikan:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Mengembalikan format teks bagan. Properti tidak berlaku untuk tipe berikut: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Baca-saja [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Mengembalikan:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Mengembalikan tema efektif untuk bagan ini.

**Mengembalikan:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Mengembalikan pengelola tema. Baca-saja [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Mengembalikan:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Menentukan bentuk yang digambar di atas bagan. Baca-saja [IGroupShape](../../com.aspose.slides/igroupshape).

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Menyediakan akses ke sumbu bagan. Baca-saja [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Mengembalikan:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Menentukan label data di atas maksimum bagan akan ditampilkan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Menentukan label data di atas maksimum bagan akan ditampilkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Menentukan area bagan memiliki sudut melengkung. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Menentukan area bagan memiliki sudut melengkung. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan bagan. Baca-saja [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)
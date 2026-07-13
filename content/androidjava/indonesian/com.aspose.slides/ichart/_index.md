---
title: IChart
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili grafik chart pada slide.
type: docs
url: /id/com.aspose.slides/ichart/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Mewakili grafik chart pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Menentukan apakah hanya sel yang terlihat yang dipetakan. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Menentukan apakah hanya sel yang terlihat yang dipetakan. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Mengembalikan atau mengatur cara memetakan sel kosong pada chart. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Mengembalikan atau mengatur cara memetakan sel kosong pada chart. |
| [getChartData()](#getChartData--) | Mengembalikan informasi tentang data yang ditautkan atau disematkan yang terkait dengan chart. |
| [hasTitle()](#hasTitle--) | Menentukan apakah chart memiliki judul yang terlihat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Menentukan apakah chart memiliki judul yang terlihat. |
| [getChartTitle()](#getChartTitle--) | Mengembalikan atau mengatur judul chart Hanya-baca [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Menentukan apakah chart memiliki tabel data. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Menentukan apakah chart memiliki tabel data. |
| [hasLegend()](#hasLegend--) | Menentukan apakah chart memiliki legenda. |
| [setLegend(boolean value)](#setLegend-boolean-) | Menentukan apakah chart memiliki legenda. |
| [getLegend()](#getLegend--) | Mengembalikan atau mengatur legenda untuk chart. |
| [getChartDataTable()](#getChartDataTable--) | Mengembalikan tabel data chart. |
| [getStyle()](#getStyle--) | Mengembalikan atau mengatur gaya chart. |
| [setStyle(int value)](#setStyle-int-) | Mengembalikan atau mengatur gaya chart. |
| [getType()](#getType--) | Mengembalikan atau mengatur tipe chart. |
| [setType(int value)](#setType-int-) | Mengembalikan atau mengatur tipe chart. |
| [getPlotArea()](#getPlotArea--) | Mewakili area plot chart. |
| [getRotation3D()](#getRotation3D--) | Mengembalikan rotasi 3D chart. |
| [getBackWall()](#getBackWall--) | Mengembalikan objek yang memungkinkan mengubah format dinding belakang chart 3D. |
| [getSideWall()](#getSideWall--) | Mengembalikan objek yang memungkinkan mengubah format dinding samping chart 3D. |
| [getFloor()](#getFloor--) | Mengembalikan objek yang memungkinkan mengubah format lantai chart 3D. |
| [getUserShapes()](#getUserShapes--) | Menentukan bentuk yang digambar di atas chart. |
| [getAxes()](#getAxes--) | Menyediakan akses ke sumbu chart. |
| [validateChartLayout()](#validateChartLayout--) | Menghitung nilai aktual elemen chart. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Menentukan label data di atas maksimum chart yang harus ditampilkan. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Menentukan label data di atas maksimum chart yang harus ditampilkan. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Menentukan area chart memiliki sudut bulat. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Menentukan area chart memiliki sudut bulat. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Menentukan apakah hanya sel yang terlihat yang dipetakan. False untuk memetakan sel yang terlihat dan tersembunyi. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Menentukan apakah hanya sel yang terlihat yang dipetakan. False untuk memetakan sel yang terlihat dan tersembunyi. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Mengembalikan atau mengatur cara memetakan sel kosong pada chart. Baca/tulis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Mengembalikan:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Mengembalikan atau mengatur cara memetakan sel kosong pada chart. Baca/tulis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Mengembalikan informasi tentang data yang ditautkan atau disematkan yang terkait dengan chart. Hanya-baca [IChartData](../../com.aspose.slides/ichartdata).

**Mengembalikan:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Menentukan apakah chart memiliki judul yang terlihat. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Menentukan apakah chart memiliki judul yang terlihat. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Mengembalikan atau mengatur judul chart Hanya-baca [IChartTitle](../../com.aspose.slides/icharttitle).

**Mengembalikan:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Menentukan apakah chart memiliki tabel data. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Menentukan apakah chart memiliki tabel data. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Menentukan apakah chart memiliki legenda. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Menentukan apakah chart memiliki legenda. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Mengembalikan atau mengatur legenda untuk chart. Hanya-baca [ILegend](../../com.aspose.slides/ilegend).

**Mengembalikan:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Mengembalikan tabel data chart. Hanya-baca [IDataTable](../../com.aspose.slides/idatatable).

**Mengembalikan:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Mengembalikan atau mengatur gaya chart. Baca/tulis [StyleType](../../com.aspose.slides/styletype).

**Mengembalikan:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Mengembalikan atau mengatur gaya chart. Baca/tulis [StyleType](../../com.aspose.slides/styletype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Mengembalikan atau mengatur tipe chart. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Mengembalikan:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Mengembalikan atau mengatur tipe chart. Baca/tulis [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Mewakili area plot chart. Hanya-baca [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Mengembalikan:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Mengembalikan rotasi 3D chart. Hanya-baca [IRotation3D](../../com.aspose.slides/irotation3d).

**Mengembalikan:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Mengembalikan objek yang memungkinkan mengubah format dinding belakang chart 3D. Hanya-baca [IChartWall](../../com.aspose.slides/ichartwall).

**Mengembalikan:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Mengembalikan objek yang memungkinkan mengubah format dinding samping chart 3D. Hanya-baca [IChartWall](../../com.aspose.slides/ichartwall).

**Mengembalikan:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Mengembalikan objek yang memungkinkan mengubah format lantai chart 3D. Hanya-baca [IChartWall](../../com.aspose.slides/ichartwall).

**Mengembalikan:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Menentukan bentuk yang digambar di atas chart. Hanya-baca [IGroupShape](../../com.aspose.slides/igroupshape).

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Menyediakan akses ke sumbu chart. Hanya-baca [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Mengembalikan:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Menghitung nilai aktual elemen chart. Nilai aktual mencakup posisi elemen yang mengimplementasikan antarmuka IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) dan nilai sumbu aktual (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Menentukan label data di atas maksimum chart yang harus ditampilkan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Menentukan label data di atas maksimum chart yang harus ditampilkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Menentukan area chart memiliki sudut bulat. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Menentukan area chart memiliki sudut bulat. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
---
title: IChart
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili bagan grafis pada slide.
type: docs
weight: 1720
url: /id/aspose.slides.charts/ichart/
---
## IChart antarmuka

Mewakili bagan grafis pada slide.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Memungkinkan untuk mendapatkan antarmuka dasar IFormattedTextContainer. Hanya-baca [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Memungkinkan untuk mendapatkan antarmuka dasar IGraphicalObject. Hanya-baca [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Mengembalikan antarmuka IOverrideThemeable. Hanya-baca [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Menyediakan akses ke sumbu bagan. Hanya-baca [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Mengembalikan objek yang memungkinkan mengubah format dinding belakang bagan 3D. Hanya-baca [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Mengembalikan informasi tentang data tertaut atau tersemat yang terkait dengan bagan. Hanya-baca [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Mengembalikan tabel data bagan. Hanya-baca [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Mengembalikan atau mengatur judul bagan. Hanya-baca [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Mengembalikan atau mengatur cara memplot sel kosong pada bagan. Baca/tulis [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Mengembalikan objek yang memungkinkan mengubah format lantai bagan 3D. Hanya-baca [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Menentukan apakah bagan memiliki tabel data. Baca/tulis Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Menentukan apakah bagan memiliki legenda. Baca/tulis Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Menentukan apakah area bagan memiliki sudut melengkung. Baca/tulis Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Menentukan apakah bagan memiliki judul yang terlihat. Baca/tulis Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Mengembalikan atau mengatur legenda bagan. Hanya-baca [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Mewakili area plot bagan. Hanya-baca [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Menentukan apakah hanya sel yang terlihat yang dipplot. False untuk memplot sel terlihat dan tersembunyi. Baca/tulis Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Mengembalikan rotasi 3D bagan. Hanya-baca [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Menentukan apakah label data pada nilai maksimum bagan harus ditampilkan. Baca/tulis Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Mengembalikan objek yang memungkinkan mengubah format dinding samping bagan 3D. Hanya-baca [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Mengembalikan atau mengatur gaya bagan. Baca/tulis [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Mengembalikan atau mengatur tipe bagan. Baca/tulis [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Menentukan bentuk yang digambar di atas bagan. Hanya-baca [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Menghitung nilai aktual elemen bagan. Nilai aktual mencakup posisi elemen yang mengimplementasikan antarmuka IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) dan nilai sumbu aktual (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Lihat Juga

* antarmuka [IFormattedTextContainer](../iformattedtextcontainer)
* antarmuka [IGraphicalObject](../../aspose.slides/igraphicalobject)
* antarmuka [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
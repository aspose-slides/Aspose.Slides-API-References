---
title: IChart
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili diagram grafis pada sebuah slide.
type: docs
weight: 1740
url: /id/aspose.slides.charts/ichart/
---
## IChart antarmuka

Mewakili diagram grafis pada sebuah slide.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Mengizinkan untuk mendapatkan antarmuka IFormattedTextContainer dasar. Hanya-baca [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Mengizinkan untuk mendapatkan antarmuka IGraphicalObject dasar. Hanya-baca [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Mengembalikan antarmuka IOverrideThemeable. Hanya-baca [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Menyediakan akses ke sumbu-sumbu diagram. Hanya-baca [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Mengembalikan objek yang memungkinkan mengubah format dinding belakang diagram 3D. Hanya-baca [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Mengembalikan informasi tentang data yang ditautkan atau disematkan yang terkait dengan diagram. Hanya-baca [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Mengembalikan tabel data diagram. Hanya-baca [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Mengembalikan atau mengatur judul diagram. Hanya-baca [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Mengembalikan atau mengatur cara menggambar sel kosong pada diagram. Baca/tulis [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Mengembalikan objek yang memungkinkan mengubah format lantai diagram 3D. Hanya-baca [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Menentukan apakah diagram memiliki tabel data. Baca/tulis Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Menentukan apakah diagram memiliki legenda. Baca/tulis Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Menentukan apakah area diagram memiliki sudut melengkung. Baca/tulis Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Menentukan apakah diagram memiliki judul yang terlihat. Baca/tulis Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Mengembalikan atau mengatur legenda untuk diagram. Hanya-baca [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Mewakili area plot diagram. Hanya-baca [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Menentukan apakah hanya sel yang terlihat yang digambar. Salah untuk menggambar sel yang terlihat dan tersembunyi. Baca/tulis Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Mengembalikan rotasi 3D diagram. Hanya-baca [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Menentukan apakah label data di atas nilai maksimum diagram harus ditampilkan. Baca/tulis Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Mengembalikan objek yang memungkinkan mengubah format dinding samping diagram 3D. Hanya-baca [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Mengembalikan atau mengatur gaya diagram. Baca/tulis [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Mengembalikan atau mengatur jenis diagram. Baca/tulis [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Menentukan bentuk-bentuk yang digambar di atas diagram. Hanya-baca [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Menghitung nilai aktual elemen-elemen diagram. Nilai aktual mencakup posisi elemen yang mengimplementasikan antarmuka IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) dan nilai sumbu aktual (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Lihat Juga

* antarmuka [IFormattedTextContainer](../iformattedtextcontainer)
* antarmuka [IGraphicalObject](../../aspose.slides/igraphicalobject)
* antarmuka [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
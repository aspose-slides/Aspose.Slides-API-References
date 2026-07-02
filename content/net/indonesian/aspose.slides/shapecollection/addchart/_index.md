---
title: AddChart
second_title: Referensi API Aspose.Sildes untuk .NET
description: Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, serta menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 100
url: /id/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | ChartType | Jenis bagan yang akan ditambahkan. |
| x | Single | Koordinat x bagan baru, dalam poin. |
| y | Single | Koordinat y bagan baru, dalam poin. |
| width | Single | Lebar bagan, dalam poin. |
| height | Single | Tinggi bagan, dalam poin. |

### Return Value

Objek [`IChart`](../../../aspose.slides.charts/ichart) yang baru dibuat.

### Examples

Contoh berikut menunjukkan cara membuat Chart dalam Presentasi PowerPoint.

```csharp
[C#]
// Membuat instance kelas Presentation yang mewakili file PPTX
using(Presentation pres = new Presentation()) {
  // Mengakses slide pertama
  ISlide sld = pres.Slides[0];
  // Menambahkan bagan dengan data defaultnya
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Menetapkan judul bagan
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Mengatur seri pertama agar menampilkan nilai
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Menetapkan indeks untuk lembar data bagan
  int defaultWorksheetIndex = 0;
  // Mengambil lembar kerja data bagan
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Menghapus seri dan kategori yang dihasilkan secara default
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Menambahkan seri baru
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Menambahkan kategori baru
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Mengambil seri bagan pertama
  IChartSeries series = chart.ChartData.Series[0];
  // Mengisi data seri
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Menetapkan warna isi untuk seri
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Mengambil seri bagan kedua
  series = chart.ChartData.Series[1];
  // Mengisi data seri
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Menetapkan warna isi untuk seri
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Menetapkan label pertama agar menampilkan nama Kategori
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Mengatur seri agar menampilkan nilai pada label ketiga
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Menyimpan file PPTX ke disk
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | ChartType | Jenis bagan yang akan ditambahkan. |
| x | Single | Koordinat x bagan baru, dalam poin. |
| y | Single | Koordinat y bagan baru, dalam poin. |
| width | Single | Lebar bagan, dalam poin. |
| height | Single | Tinggi bagan, dalam poin. |
| initWithSample | Boolean | True untuk menginisialisasi bagan baru dengan data seri contoh dan pengaturan; false untuk membuat bagan tanpa seri dan hanya pengaturan minimal, yang mempercepat pembuatan. |

### Return Value

Objek [`IChart`](../../../aspose.slides.charts/ichart) yang baru dibuat.

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: AddChartFromWorkbook
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengambil bagan dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.
type: docs
weight: 10
url: /id/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Mengambil bagan dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | IShapeCollection | Koleksi bentuk yang akan ditambahkan bagan. |
| x | Single | Koordinat X untuk menempatkan bagan. |
| y | Single | Koordinat Y untuk menempatkan bagan. |
| workbook | IExcelDataWorkbook | Workbook Excel. |
| worksheetName | String | Nama lembar kerja yang berisi bagan. |
| chartIndex | Int32 | Indeks berbasis nol dari bentuk bagan yang akan disisipkan. Indeks ini dapat diperoleh menggunakan metode [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet). |
| embedAllWorkbook | Boolean | Jika `true`, seluruh workbook akan disematkan ke dalam bagan; jika `false`, hanya data bagan yang akan disematkan. |

### Nilai Kembali

Bagan yang ditambahkan ke koleksi bentuk.

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika parameter yang diperlukan bernilai null, kosong, atau jika bagan tidak dapat ditemukan dalam workbook. |

### Contoh

Contoh:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Mengambil bagan dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | IShapeCollection | Koleksi bentuk yang akan ditambahkan bagan. |
| x | Single | Koordinat X untuk menempatkan bagan. |
| y | Single | Koordinat Y untuk menempatkan bagan. |
| workbook | IExcelDataWorkbook | Workbook Excel. |
| worksheetName | String | Nama lembar kerja yang berisi bagan. |
| chartName | String | Nama bagan yang akan ditambahkan. |
| embedAllWorkbook | Boolean | Jika `true`, seluruh workbook akan disematkan ke dalam bagan; jika `false`, hanya data bagan yang akan disematkan. |

### Nilai Kembali

Bagan yang ditambahkan ke koleksi bentuk.

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika parameter yang diperlukan bernilai null, kosong, atau jika bagan tidak dapat ditemukan dalam workbook. |

### Contoh

Contoh:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Mengambil bagan dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | IShapeCollection | Koleksi bentuk yang akan ditambahkan bagan. |
| x | Single | Koordinat X untuk menempatkan bagan. |
| y | Single | Koordinat Y untuk menempatkan bagan. |
| workbookStream | Stream | Aliran yang berisi data workbook. |
| worksheetName | String | Nama lembar kerja yang berisi bagan. |
| chartName | String | Nama bagan yang akan ditambahkan. |
| embedAllWorkbook | Boolean | Jika `true`, seluruh workbook akan disematkan ke dalam bagan; jika `false`, hanya data bagan yang akan disematkan. |

### Nilai Kembali

Bagan yang ditambahkan ke koleksi bentuk.

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika parameter yang diperlukan bernilai null, kosong, atau jika bagan tidak dapat ditemukan dalam workbook. |
| InvalidOperationException | Dilempar ketika data masukan berada dalam format yang tidak didukung. |

### Contoh

Contoh:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Mengambil bagan dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | IShapeCollection | Koleksi bentuk yang akan ditambahkan bagan. |
| x | Single | Koordinat X untuk menempatkan bagan. |
| y | Single | Koordinat Y untuk menempatkan bagan. |
| workbookPath | String | Jalur file ke workbook yang berisi bagan. |
| worksheetName | String | Nama lembar kerja yang berisi bagan. |
| chartName | String | Nama bagan yang akan ditambahkan. |
| embedWorkbook | Boolean | Jika `true`, workbook akan disematkan ke dalam bagan; jika `false`, bagan akan menaut ke workbook eksternal. |

### Nilai Kembali

Bagan yang ditambahkan ke koleksi bentuk.

### Pengecualian

| Pengecualian | Kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika parameter yang diperlukan bernilai null, kosong, atau jika bagan tidak dapat ditemukan dalam workbook. |
| IOException | Dilempar ketika terjadi kesalahan I/O saat mengakses file. |
| InvalidOperationException | Dilempar ketika data masukan berada dalam format yang tidak didukung. |

### Contoh

Contoh:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: AddTableFromWorkbook
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengambil tabel dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.
type: docs
weight: 20
url: /id/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Mengambil tabel dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | IShapeCollection | Koleksi bentuk tempat tabel akan ditambahkan. |
| x | Single | Koordinat X untuk memposisikan tabel. |
| y | Single | Koordinat Y untuk memposisikan tabel. |
| workbook | IExcelDataWorkbook | Workbook Excel. |
| worksheetName | String | Nama lembar kerja yang berisi tabel. |
| cellRange | String | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

### Nilai Kembalian

Tabel yang telah ditambahkan ke koleksi bentuk.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika ada parameter wajib yang null atau kosong, atau ketika lembar kerja atau rentang sel yang ditentukan tidak valid. |
| InvalidOperationException | Dilempar ketika data input berada dalam format yang tidak didukung. |

### Contoh

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* antarmuka [ITable](../../../aspose.slides/itable)
* antarmuka [IShapeCollection](../../../aspose.slides/ishapecollection)
* antarmuka [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* kelas [ExcelWorkbookImporter](../../excelworkbookimporter)
* ruang nama [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Mengambil tabel dari file workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | IShapeCollection | Koleksi bentuk tempat tabel akan ditambahkan. |
| x | Single | Koordinat X untuk memposisikan tabel. |
| y | Single | Koordinat Y untuk memposisikan tabel. |
| workbookPath | String | Jalur ke file workbook Excel. |
| worksheetName | String | Nama lembar kerja yang berisi tabel. |
| cellRange | String | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

### Nilai Kembalian

Tabel yang telah ditambahkan ke koleksi bentuk.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika ada parameter wajib yang null atau kosong, atau ketika lembar kerja atau rentang sel yang ditentukan tidak valid. |
| IOException | Dilempar ketika terjadi kesalahan I/O saat mengakses file workbook. |
| InvalidOperationException | Dilempar ketika data input berada dalam format yang tidak didukung. |

### Contoh

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* antarmuka [ITable](../../../aspose.slides/itable)
* antarmuka [IShapeCollection](../../../aspose.slides/ishapecollection)
* kelas [ExcelWorkbookImporter](../../excelworkbookimporter)
* ruang nama [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Mengambil tabel dari file workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi bentuk yang diberikan pada koordinat yang ditentukan.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | IShapeCollection | Koleksi bentuk tempat tabel akan ditambahkan. |
| x | Single | Koordinat X untuk memposisikan tabel. |
| y | Single | Koordinat Y untuk memposisikan tabel. |
| workbookStream | Stream | Aliran yang berisi data workbook. |
| worksheetName | String | Nama lembar kerja yang berisi tabel. |
| cellRange | String | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

### Nilai Kembalian

Tabel yang telah ditambahkan ke koleksi bentuk.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika ada parameter wajib yang null atau kosong, atau ketika lembar kerja atau rentang sel yang ditentukan tidak valid. |
| InvalidOperationException | Dilempar ketika data input berada dalam format yang tidak didukung. |

### Contoh

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* antarmuka [ITable](../../../aspose.slides/itable)
* antarmuka [IShapeCollection](../../../aspose.slides/ishapecollection)
* kelas [ExcelWorkbookImporter](../../excelworkbookimporter)
* ruang nama [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
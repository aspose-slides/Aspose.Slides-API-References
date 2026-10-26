---
title: AddTableFromWorkbook()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil tabel dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.
type: docs
weight: 14
url: /id/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) metode

Mengambil tabel dari workbook [Excel](../../../aspose.slides.excel/) yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Koleksi shape ke mana tabel akan ditambahkan. |
| x | **float** | Koordinat X untuk menempatkan tabel. |
| y | **float** | Koordinat Y untuk menempatkan tabel. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Nama worksheet yang berisi tabel. |
| cellRange | [System::String](../../../system/string/) | Rentang sel yang menentukan tabel (misalnya, "A1:D10"). |

### Nilai Kembali

Tabel yang ditambahkan ke koleksi shape.

## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) metode

Mengambil tabel dari file workbook [Excel](../../../aspose.slides.excel/) yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Koleksi shape ke mana tabel akan ditambahkan. |
| x | **float** | Koordinat X untuk menempatkan tabel. |
| y | **float** | Koordinat Y untuk menempatkan tabel. |
| workbookPath | [System::String](../../../system/string/) | Path ke file workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Nama worksheet yang berisi tabel. |
| cellRange | [System::String](../../../system/string/) | Rentang sel yang menentukan tabel (misalnya, "A1:D10"). |

### Nilai Kembali

Tabel yang ditambahkan ke koleksi shape.

## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) metode

Mengambil tabel dari file workbook [Excel](../../../aspose.slides.excel/) yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Koleksi shape ke mana tabel akan ditambahkan. |
| x | **float** | Koordinat X untuk menempatkan tabel. |
| y | **float** | Koordinat Y untuk menempatkan tabel. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream yang berisi data workbook. |
| worksheetName | [System::String](../../../system/string/) | Nama worksheet yang berisi tabel. |
| cellRange | [System::String](../../../system/string/) | Rentang sel yang menentukan tabel (misalnya, "A1:D10"). |

### Nilai Kembali

Tabel yang ditambahkan ke koleksi shape.

## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITable](../../../aspose.slides/itable/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)
---
title: AddChartFromWorkbook()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil sebuah bagan dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.
type: docs
weight: 1
url: /id/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) metode

Mengambil sebuah bagan dari workbook [Excel](../../../aspose.slides.excel/) yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Koleksi shape yang akan ditambahkan bagan. |
| x | **float** | Koordinat X untuk menempatkan bagan. |
| y | **float** | Koordinat Y untuk menempatkan bagan. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Buku kerja [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Nama worksheet yang berisi bagan. |
| chartIndex | **int32_t** | Indeks nol berbasis untuk shape bagan yang akan disisipkan. Indeks ini dapat diperoleh menggunakan metode [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Jika **true**, seluruh workbook akan disematkan dalam bagan; jika **false**, hanya data bagan yang akan disematkan. |

### Nilai Kembalian

Bagan yang telah ditambahkan ke koleksi shape.
## Catatan

Contoh: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) metode

Mengambil sebuah bagan dari workbook [Excel](../../../aspose.slides.excel/) yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Koleksi shape yang akan ditambahkan bagan. |
| x | **float** | Koordinat X untuk menempatkan bagan. |
| y | **float** | Koordinat Y untuk menempatkan bagan. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Buku kerja [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Nama worksheet yang berisi bagan. |
| chartName | [System::String](../../../system/string/) | Nama bagan yang akan ditambahkan. |
| embedAllWorkbook | **bool** | Jika **true**, seluruh workbook akan disematkan dalam bagan; jika **false**, hanya data bagan yang akan disematkan. |

### Nilai Kembalian

Bagan yang telah ditambahkan ke koleksi shape.
## Catatan

Contoh: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();

System::String worksheetName = u"worksheet name";
auto worksheetCharts = wb->GetChartsFromWorksheet(worksheetName);
for (auto&& chart : worksheetCharts)
{
    System::SharedPtr<ISlide> slide = pres->get_Slides()->AddEmptySlide(pres->get_LayoutSlides()->idx_get(0));
    ExcelWorkbookImporter::AddChartFromWorkbook(slide->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chart.get_Key(), false);
}
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) metode

Mengambil sebuah bagan dari workbook [Excel](../../../aspose.slides.excel/) yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Koleksi shape yang akan ditambahkan bagan. |
| x | **float** | Koordinat X untuk menempatkan bagan. |
| y | **float** | Koordinat Y untuk menempatkan bagan. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran yang berisi data workbook. |
| worksheetName | [System::String](../../../system/string/) | Nama worksheet yang berisi bagan. |
| chartName | [System::String](../../../system/string/) | Nama bagan yang akan ditambahkan. |
| embedAllWorkbook | **bool** | Jika **true**, seluruh workbook akan disematkan dalam bagan; jika **false**, hanya data bagan yang akan disematkan. |

### Nilai Kembalian

Bagan yang telah ditambahkan ke koleksi shape.
## Catatan

Contoh: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) metode

Mengambil sebuah bagan dari workbook [Excel](../../../aspose.slides.excel/) yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Koleksi shape yang akan ditambahkan bagan. |
| x | **float** | Koordinat X untuk menempatkan bagan. |
| y | **float** | Koordinat Y untuk menempatkan bagan. |
| workbookPath | [System::String](../../../system/string/) | Jalur file ke workbook yang berisi bagan. |
| worksheetName | [System::String](../../../system/string/) | Nama worksheet yang berisi bagan. |
| chartName | [System::String](../../../system/string/) | Nama bagan yang akan ditambahkan. |
| embedWorkbook | **bool** | Jika **true**, workbook akan disematkan dalam bagan; jika **false**, bagan akan menaut ke workbook eksternal. |

### Nilai Kembalian

Bagan yang telah ditambahkan ke koleksi shape.
## Catatan

Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)
---
title: AddTableFromWorkbook()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen Excel çalışma kitabından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.
type: docs
weight: 14
url: /tr/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method


Belirtilen [Excel](../../../aspose.slides.excel/) çalışma kitabından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Tabloyun ekleneceği şekil koleksiyonu. |
| x | **float** | Tabloyu konumlandırmak için X koordinatı. |
| y | **float** | Tabloyu konumlandırmak için Y koordinatı. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) çalışma kitabı. |
| worksheetName | [System::String](../../../system/string/) | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | [System::String](../../../system/string/) | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### Dönüş Değeri

Şekil koleksiyonuna eklenen tablo.
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method


Belirtilen [Excel](../../../aspose.slides.excel/) çalışma kitabı dosyasından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Tabloyun ekleneceği şekil koleksiyonu. |
| x | **float** | Tabloyu konumlandırmak için X koordinatı. |
| y | **float** | Tabloyu konumlandırmak için Y koordinatı. |
| workbookPath | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) çalışma kitabı dosyasının yolu. |
| worksheetName | [System::String](../../../system/string/) | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | [System::String](../../../system/string/) | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### Dönüş Değeri

Şekil koleksiyonuna eklenen tablo.
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method


Belirtilen [Excel](../../../aspose.slides.excel/) çalışma kitabı dosyasından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Tabloyun ekleneceği şekil koleksiyonu. |
| x | **float** | Tabloyu konumlandırmak için X koordinatı. |
| y | **float** | Tabloyu konumlandırmak için Y koordinatı. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Çalışma kitabı verilerini içeren akış. |
| worksheetName | [System::String](../../../system/string/) | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | [System::String](../../../system/string/) | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### Dönüş Değeri

Şekil koleksiyonuna eklenen tablo.
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ITable](../../../aspose.slides/itable/)
* Sınıf [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Sınıf [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Sınıf [String](../../../system/string/)
* Sınıf [ExcelWorkbookImporter](../)
* Sınıf [Stream](../../../system.io/stream/)
* Ad Alanı [Aspose::Slides::Import](../../)
* Kütüphane [Aspose.Slides](../../../)
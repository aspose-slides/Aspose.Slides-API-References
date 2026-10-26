---
title: AddChartFromWorkbook()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.
type: docs
weight: 1
url: /tr/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method

Belirtilen [Excel](../../../aspose.slides.excel/) çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Grafiğin ekleneceği şekil koleksiyonu. |
| x | **float** | Grafiği konumlandırmak için X koordinatı. |
| y | **float** | Grafiği konumlandırmak için Y koordinatı. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) çalışma kitabı. |
| worksheetName | [System::String](../../../system/string/) | Grafiği içeren çalışma sayfasının adı. |
| chartIndex | **int32_t** | Grafik şeklinin eklenmesi için sıfır tabanlı indeks. Bu indeks [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) yöntemiyle alınabilir. |
| embedAllWorkbook | **bool** | **true** ise, tüm çalışma kitabı grafik içine gömülür; **false** ise, yalnızca grafik verileri gömülür. |

### Dönüş Değeri

Şekil koleksiyonuna eklenen grafik.

## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method

Belirtilen [Excel](../../../aspose.slides.excel/) çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Grafiğin ekleneceği şekil koleksiyonu. |
| x | **float** | Grafiği konumlandırmak için X koordinatı. |
| y | **float** | Grafiği konumlandırmak için Y koordinatı. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) çalışma kitabı. |
| worksheetName | [System::String](../../../system/string/) | Grafiği içeren çalışma sayfasının adı. |
| chartName | [System::String](../../../system/string/) | Eklenecek grafiğin adı. |
| embedAllWorkbook | **bool** | **true** ise, tüm çalışma kitabı grafik içine gömülür; **false** ise, yalnızca grafik verileri gömülür. |

### Dönüş Değeri

Şekil koleksiyonuna eklenen grafik.

## Açıklamalar



Örnek: 
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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) method

Belirtilen [Excel](../../../aspose.slides.excel/) çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Grafiğin ekleneceği şekil koleksiyonu. |
| x | **float** | Grafiği konumlandırmak için X koordinatı. |
| y | **float** | Grafiği konumlandırmak için Y koordinatı. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Çalışma kitabı verilerini içeren akış. |
| worksheetName | [System::String](../../../system/string/) | Grafiği içeren çalışma sayfasının adı. |
| chartName | [System::String](../../../system/string/) | Eklenecek grafiğin adı. |
| embedAllWorkbook | **bool** | **true** ise, tüm çalışma kitabı grafik içine gömülür; **false** ise, yalnızca grafik verileri gömülür. |

### Dönüş Değeri

Şekil koleksiyonuna eklenen grafik.

## Açıklamalar



Örnek: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method

Belirtilen [Excel](../../../aspose.slides.excel/) çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Grafiğin ekleneceği şekil koleksiyonu. |
| x | **float** | Grafiği konumlandırmak için X koordinatı. |
| y | **float** | Grafiği konumlandırmak için Y koordinatı. |
| workbookPath | [System::String](../../../system/string/) | Grafiği içeren çalışma kitabının dosya yolu. |
| worksheetName | [System::String](../../../system/string/) | Grafiği içeren çalışma sayfasının adı. |
| chartName | [System::String](../../../system/string/) | Eklenecek grafiğin adı. |
| embedWorkbook | **bool** | **true** ise, çalışma kitabı grafik içine gömülür; **false** ise, grafik harici çalışma kitabına bağlanır. |

### Dönüş Değeri

Şekil koleksiyonuna eklenen grafik.

## Açıklamalar



Örnek: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Ayrıca

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChart](../../../aspose.slides.charts/ichart/)
* Sınıf [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Sınıf [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Sınıf [String](../../../system/string/)
* Sınıf [ExcelWorkbookImporter](../)
* Sınıf [Stream](../../../system.io/stream/)
* Ad Alanı [Aspose::Slides::Import](../../)
* Kütüphane [Aspose.Slides](../../../)
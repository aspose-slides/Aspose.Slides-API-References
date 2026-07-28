---
title: AddChartFromWorkbook()
second_title: Aspose.Slides C++-hoz API referencia
description: Lekéri a diagramot a megadott Excel munkafüzetből, és a megadott koordinátákon a megadott alakgyűjtemény végéhez adja hozzá.
type: docs
weight: 1
url: /hu/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method


A megadott [Excel](../../../aspose.slides.excel/) munkafüzetből lekéri a diagramot, és a megadott koordinátákon a megadott alakgyűjtemény végére adja hozzá.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Az alakgyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | **float** | A diagram elhelyezéséhez szükséges X koordináta. |
| y | **float** | A diagram elhelyezéséhez szükséges Y koordináta. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | A [Excel](../../../aspose.slides.excel/) munkafüzet. |
| worksheetName | [System::String](../../../system/string/) | A diagramot tartalmazó munkalap neve. |
| chartIndex | **int32_t** | A beszúrandó diagram alak indexe nullától kezdődően. Ez az index a [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) metódussal szerezhető be. |
| embedAllWorkbook | **bool** | Ha **true**, a teljes munkafüzet be lesz ágyazva a diagramba; ha **false**, csak a diagram adatai lesznek beágyazva. |

### Visszatérési érték

A alakgyűjteményhez hozzáadott diagram.
## Megjegyzések



Példa: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method


A megadott [Excel](../../../aspose.slides.excel/) munkafüzetből lekéri a diagramot, és a megadott koordinátákon a megadott alakgyűjtemény végére adja hozzá.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Az alakgyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | **float** | A diagram elhelyezéséhez szükséges X koordináta. |
| y | **float** | A diagram elhelyezéséhez szükséges Y koordináta. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | A [Excel](../../../aspose.slides.excel/) munkafüzet. |
| worksheetName | [System::String](../../../system/string/) | A diagramot tartalmazó munkalap neve. |
| chartName | [System::String](../../../system/string/) | A hozzáadandó diagram neve. |
| embedAllWorkbook | **bool** | Ha **true**, a teljes munkafüzet be lesz ágyazva a diagramba; ha **false**, csak a diagram adatai lesznek beágyazva. |

### Visszatérési érték

A alakgyűjteményhez hozzáadott diagram.
## Megjegyzések



Példa: 
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


A megadott [Excel](../../../aspose.slides.excel/) munkafüzetből lekéri a diagramot, és a megadott koordinátákon a megadott alakgyűjtemény végére adja hozzá.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Az alakgyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | **float** | A diagram elhelyezéséhez szükséges X koordináta. |
| y | **float** | A diagram elhelyezéséhez szükséges Y koordináta. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A munkafüzet adatokat tartalmazó adatfolyam. |
| worksheetName | [System::String](../../../system/string/) | A diagramot tartalmazó munkalap neve. |
| chartName | [System::String](../../../system/string/) | A hozzáadandó diagram neve. |
| embedAllWorkbook | **bool** | Ha **true**, a teljes munkafüzet be lesz ágyazva a diagramba; ha **false**, csak a diagram adatai lesznek beágyazva. |

### Visszatérési érték

A alakgyűjteményhez hozzáadott diagram.
## Megjegyzések



Példa: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method


A megadott [Excel](../../../aspose.slides.excel/) munkafüzetből lekéri a diagramot, és a megadott koordinátákon a megadott alakgyűjtemény végére adja hozzá.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Az alakgyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | **float** | A diagram elhelyezéséhez szükséges X koordináta. |
| y | **float** | A diagram elhelyezéséhez szükséges Y koordináta. |
| workbookPath | [System::String](../../../system/string/) | A diagramot tartalmazó munkafüzet fájl útvonala. |
| worksheetName | [System::String](../../../system/string/) | A diagramot tartalmazó munkalap neve. |
| chartName | [System::String](../../../system/string/) | A hozzáadandó diagram neve. |
| embedWorkbook | **bool** | Ha **true**, a munkafüzet be lesz ágyazva a diagramba; ha **false**, a diagram külső munkafüzetre fog hivatkozni. |

### Visszatérési érték

A alakgyűjteményhez hozzáadott diagram.
## Megjegyzések



Példa: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)
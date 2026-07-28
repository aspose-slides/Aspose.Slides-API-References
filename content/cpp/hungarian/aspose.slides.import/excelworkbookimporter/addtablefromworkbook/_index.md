---
title: AddTableFromWorkbook()
second_title: Aspose.Slides C++ API Referenciája
description: Lekéri a táblázatot a megadott Excel munkafüzetből, és a megadott koordinátákon a megadott alakgyűjtemény végére adja hozzá.
type: docs
weight: 14
url: /hu/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) metódus


A megadott [Excel](../../../aspose.slides.excel/) munkafüzetből lekéri a táblázatot, és a megadott koordinátákon a megadott alakgyűjtemény végére adja hozzá.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Az alakgyűjtemény, amelyhez a táblázat hozzá lesz adva. |
| x | **float** | Az X koordináta a táblázat elhelyezéséhez. |
| y | **float** | Az Y koordináta a táblázat elhelyezéséhez. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | A [Excel](../../../aspose.slides.excel/) munkafüzet. |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | [System::String](../../../system/string/) | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

### Visszatérési érték

A táblázat, amely hozzá lett adva az alakgyűjteményhez.
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) metódus


A megadott [Excel](../../../aspose.slides.excel/) munkafüzetfájlból lekéri a táblázatot, és a megadott koordinátákon a megadott alakgyűjtemény végére adja hozzá.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Az alakgyűjtemény, amelyhez a táblázat hozzá lesz adva. |
| x | **float** | Az X koordináta a táblázat elhelyezéséhez. |
| y | **float** | Az Y koordináta a táblázat elhelyezéséhez. |
| workbookPath | [System::String](../../../system/string/) | Az útvonal a [Excel](../../../aspose.slides.excel/) munkafüzetfájlhoz. |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | [System::String](../../../system/string/) | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

### Visszatérési érték

A táblázat, amely hozzá lett adva az alakgyűjteményhez.
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) metódus


A megadott [Excel](../../../aspose.slides.excel/) munkafüzetfájlból lekéri a táblázatot, és a megadott koordinátákon a megadott alakgyűjtemény végére adja hozzá.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Az alakgyűjtemény, amelyhez a táblázat hozzá lesz adva. |
| x | **float** | Az X koordináta a táblázat elhelyezéséhez. |
| y | **float** | Az Y koordináta a táblázat elhelyezéséhez. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Az adatfolyam, amely a munkafüzet adatát tartalmazza. |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | [System::String](../../../system/string/) | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

### Visszatérési érték

A táblázat, amely hozzá lett adva az alakgyűjteményhez.
## Megjegyzések 




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdef [SharedPtr](../../../system/sharedptr/)
* Osztály [ITable](../../../aspose.slides/itable/)
* Osztály [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Osztály [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Osztály [String](../../../system/string/)
* Osztály [ExcelWorkbookImporter](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides::Import](../../)
* Könyvtár [Aspose.Slides](../../../)
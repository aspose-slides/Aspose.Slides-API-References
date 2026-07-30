---
title: AddTableFromWorkbook()
second_title: Aspose.Slides pro C++ API Reference
description: Načte tabulku ze zadaného sešitu Excel a přidá ji na konec dané kolekce tvarů na uvedených souřadnicích.
type: docs
weight: 14
url: /cs/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method


Načte tabulku ze zadaného [Excel](../../../aspose.slides.excel/) sešitu a přidá ji na konec dané kolekce tvarů na zadaných souřadnicích.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekce tvarů, do které bude tabulka přidána. |
| x | **float** | Souřadnice X pro umístění tabulky. |
| y | **float** | Souřadnice Y pro umístění tabulky. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) sešit. |
| worksheetName | [System::String](../../../system/string/) | Název listu obsahujícího tabulku. |
| cellRange | [System::String](../../../system/string/) | Rozsah buněk definující tabulku (například "A1:D10"). |

### Návratová hodnota

Tabulka, která byla přidána do kolekce tvarů.
## Poznámky




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method


Načte tabulku ze zadaného [Excel](../../../aspose.slides.excel/) souboru sešitu a přidá ji na konec dané kolekce tvarů na zadaných souřadnicích.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekce tvarů, do které bude tabulka přidána. |
| x | **float** | Souřadnice X pro umístění tabulky. |
| y | **float** | Souřadnice Y pro umístění tabulky. |
| workbookPath | [System::String](../../../system/string/) | Cesta k souboru sešitu [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Název listu obsahujícího tabulku. |
| cellRange | [System::String](../../../system/string/) | Rozsah buněk definující tabulku (například "A1:D10"). |

### Návratová hodnota

Tabulka, která byla přidána do kolekce tvarů.
## Poznámky




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method


Načte tabulku ze zadaného [Excel](../../../aspose.slides.excel/) souboru sešitu a přidá ji na konec dané kolekce tvarů na zadaných souřadnicích.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekce tvarů, do které bude tabulka přidána. |
| x | **float** | Souřadnice X pro umístění tabulky. |
| y | **float** | Souřadnice Y pro umístění tabulky. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud obsahující data sešitu. |
| worksheetName | [System::String](../../../system/string/) | Název listu obsahujícího tabulku. |
| cellRange | [System::String](../../../system/string/) | Rozsah buněk definující tabulku (například "A1:D10"). |

### Návratová hodnota

Tabulka, která byla přidána do kolekce tvarů.
## Poznámky




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Další související informace

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ITable](../../../aspose.slides/itable/)
* Třída [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Třída [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Třída [String](../../../system/string/)
* Třída [ExcelWorkbookImporter](../)
* Třída [Stream](../../../system.io/stream/)
* Obor názvů [Aspose::Slides::Import](../../)
* Knihovna [Aspose.Slides](../../../)
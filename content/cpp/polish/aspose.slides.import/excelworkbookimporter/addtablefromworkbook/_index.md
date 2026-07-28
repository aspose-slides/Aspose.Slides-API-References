---
title: AddTableFromWorkbook()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera tabelę z określonego skoroszytu Excel i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych.
type: docs
weight: 14
url: /pl/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method


Pobiera tabelę z określonego [Excel](../../../aspose.slides.excel/) skoroszytu i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekcja kształtów, do której zostanie dodana tabela. |
| x | **float** | Współrzędna X położenia tabeli. |
| y | **float** | Współrzędna Y położenia tabeli. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Skoroszyt [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, który zawiera tabelę. |
| cellRange | [System::String](../../../system/string/) | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Wartość zwracana

Tabela, która została dodana do kolekcji kształtów.
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method


Pobiera tabelę z określonego pliku skoroszytu [Excel](../../../aspose.slides.excel/) i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekcja kształtów, do której zostanie dodana tabela. |
| x | **float** | Współrzędna X położenia tabeli. |
| y | **float** | Współrzędna Y położenia tabeli. |
| workbookPath | [System::String](../../../system/string/) | Ścieżka do pliku skoroszytu [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, który zawiera tabelę. |
| cellRange | [System::String](../../../system/string/) | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Wartość zwracana

Tabela, która została dodana do kolekcji kształtów.
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method


Pobiera tabelę z określonego pliku skoroszytu [Excel](../../../aspose.slides.excel/) i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekcja kształtów, do której zostanie dodana tabela. |
| x | **float** | Współrzędna X położenia tabeli. |
| y | **float** | Współrzędna Y położenia tabeli. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień zawierający dane skoroszytu. |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, który zawiera tabelę. |
| cellRange | [System::String](../../../system/string/) | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Wartość zwracana

Tabela, która została dodana do kolekcji kształtów.
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ITable](../../../aspose.slides/itable/)
* Klasa [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Klasa [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Klasa [String](../../../system/string/)
* Klasa [ExcelWorkbookImporter](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)
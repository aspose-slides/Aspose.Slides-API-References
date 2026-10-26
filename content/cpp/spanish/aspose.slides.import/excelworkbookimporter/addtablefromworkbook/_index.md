---
title: AddTableFromWorkbook()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene una tabla del libro de trabajo de Excel especificado y la añade al final de la colección de formas proporcionada en las coordenadas especificadas.
type: docs
weight: 14
url: /es/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method


Obtiene una tabla del libro de trabajo [Excel](../../../aspose.slides.excel/) especificado y la añade al final de la colección de formas proporcionada en las coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La colección de formas a la que se añadirá la tabla. |
| x | **float** | La coordenada X para posicionar la tabla. |
| y | **float** | La coordenada Y para posicionar la tabla. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | El libro de trabajo [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo que contiene la tabla. |
| cellRange | [System::String](../../../system/string/) | El rango de celdas que define la tabla (por ejemplo, \"A1:D10\"). |

### Valor de retorno

La tabla que se añadió a la colección de formas.
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method


Obtiene una tabla del archivo de libro de trabajo [Excel](../../../aspose.slides.excel/) especificado y la añade al final de la colección de formas proporcionada en las coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La colección de formas a la que se añadirá la tabla. |
| x | **float** | La coordenada X para posicionar la tabla. |
| y | **float** | La coordenada Y para posicionar la tabla. |
| workbookPath | [System::String](../../../system/string/) | La ruta al archivo de libro de trabajo [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo que contiene la tabla. |
| cellRange | [System::String](../../../system/string/) | El rango de celdas que define la tabla (por ejemplo, \"A1:D10\"). |

### Valor de retorno

La tabla que se añadió a la colección de formas.
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method


Obtiene una tabla del archivo de libro de trabajo [Excel](../../../aspose.slides.excel/) especificado y la añade al final de la colección de formas proporcionada en las coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La colección de formas a la que se añadirá la tabla. |
| x | **float** | La coordenada X para posicionar la tabla. |
| y | **float** | La coordenada Y para posicionar la tabla. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flujo que contiene los datos del libro de trabajo. |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo que contiene la tabla. |
| cellRange | [System::String](../../../system/string/) | El rango de celdas que define la tabla (por ejemplo, \"A1:D10\"). |

### Valor de retorno

La tabla que se añadió a la colección de formas.
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ITable](../../../aspose.slides/itable/)
* Clase [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Clase [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Clase [String](../../../system/string/)
* Clase [ExcelWorkbookImporter](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides::Import](../../)
* Biblioteca [Aspose.Slides](../../../)
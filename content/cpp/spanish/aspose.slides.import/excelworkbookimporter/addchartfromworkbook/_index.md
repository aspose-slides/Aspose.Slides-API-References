---
title: AddChartFromWorkbook()
second_title: Referencia de API de Aspose.Slides para C++
description: Recupera un gráfico del libro de trabajo Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.
type: docs
weight: 1
url: /es/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) método

Recupera un gráfico del libro de trabajo [Excel](../../../aspose.slides.excel/) especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La colección de formas a la que se añadirá el gráfico. |
| x | **float** | La coordenada X para posicionar el gráfico. |
| y | **float** | La coordenada Y para posicionar el gráfico. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | El libro de trabajo [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo que contiene el gráfico. |
| chartIndex | **int32_t** | El índice base cero de la forma del gráfico a insertar. Este índice se puede obtener mediante el método [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Si **true**, todo el libro de trabajo se incrustará en el gráfico; si **false**, solo se incrustarán los datos del gráfico. |

### Valor de retorno

El gráfico que se añadió a la colección de formas.

## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) método


Recupera un gráfico del libro de trabajo [Excel](../../../aspose.slides.excel/) especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La colección de formas a la que se añadirá el gráfico. |
| x | **float** | La coordenada X para posicionar el gráfico. |
| y | **float** | La coordenada Y para posicionar el gráfico. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | El libro de trabajo [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo que contiene el gráfico. |
| chartName | [System::String](../../../system/string/) | El nombre del gráfico que se añadirá. |
| embedAllWorkbook | **bool** | Si **true**, todo el libro de trabajo se incrustará en el gráfico; si **false**, solo se incrustarán los datos del gráfico. |

### Valor de retorno

El gráfico que se añadió a la colección de formas.

## Observaciones



Ejemplo: 
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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) método


Recupera un gráfico del libro de trabajo [Excel](../../../aspose.slides.excel/) especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La colección de formas a la que se añadirá el gráfico. |
| x | **float** | La coordenada X para posicionar el gráfico. |
| y | **float** | La coordenada Y para posicionar el gráfico. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flujo que contiene los datos del libro de trabajo. |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo que contiene el gráfico. |
| chartName | [System::String](../../../system/string/) | El nombre del gráfico que se añadirá. |
| embedAllWorkbook | **bool** | Si **true**, todo el libro de trabajo se incrustará en el gráfico; si **false**, solo se incrustarán los datos del gráfico. |

### Valor de retorno

El gráfico que se añadió a la colección de formas.

## Observaciones



Ejemplo: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) método


Recupera un gráfico del libro de trabajo [Excel](../../../aspose.slides.excel/) especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La colección de formas a la que se añadirá el gráfico. |
| x | **float** | La coordenada X para posicionar el gráfico. |
| y | **float** | La coordenada Y para posicionar el gráfico. |
| workbookPath | [System::String](../../../system/string/) | La ruta del archivo del libro de trabajo que contiene el gráfico. |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo que contiene el gráfico. |
| chartName | [System::String](../../../system/string/) | El nombre del gráfico que se añadirá. |
| embedWorkbook | **bool** | Si **true**, el libro de trabajo se incrustará en el gráfico; si **false**, el gráfico enlazará al libro de trabajo externo. |

### Valor de retorno

El gráfico que se añadió a la colección de formas.

## Observaciones



Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChart](../../../aspose.slides.charts/ichart/)
* Clase [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Clase [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Clase [String](../../../system/string/)
* Clase [ExcelWorkbookImporter](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides::Import](../../)
* Biblioteca [Aspose.Slides](../../../)
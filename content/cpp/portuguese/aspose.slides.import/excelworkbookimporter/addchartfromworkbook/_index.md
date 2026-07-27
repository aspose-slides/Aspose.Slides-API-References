---
title: AddChartFromWorkbook()
second_title: Referência da API Aspose.Slides para C++
description: Recupera um gráfico do workbook Excel especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.
type: docs
weight: 1
url: /pt/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method

Recupera um gráfico do workbook [Excel](../../../aspose.slides.excel/) especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | A coleção de formas à qual o gráfico será adicionado. |
| x | **float** | A coordenada X para posicionar o gráfico. |
| y | **float** | A coordenada Y para posicionar o gráfico. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | O workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha que contém o gráfico. |
| chartIndex | **int32_t** | O índice baseado em zero da forma de gráfico a ser inserida. Esse índice pode ser obtido usando o método [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Se **true**, todo o workbook será incorporado ao gráfico; se **false**, apenas os dados do gráfico serão incorporados. |

### Valor de retorno

O gráfico que foi adicionado à coleção de formas.

## Observações



Exemplo: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method

Recupera um gráfico do workbook [Excel](../../../aspose.slides.excel/) especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | A coleção de formas à qual o gráfico será adicionado. |
| x | **float** | A coordenada X para posicionar o gráfico. |
| y | **float** | A coordenada Y para posicionar o gráfico. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | O workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha que contém o gráfico. |
| chartName | [System::String](../../../system/string/) | O nome do gráfico a ser adicionado. |
| embedAllWorkbook | **bool** | Se **true**, todo o workbook será incorporado ao gráfico; se **false**, apenas os dados do gráfico serão incorporados. |

### Valor de retorno

O gráfico que foi adicionado à coleção de formas.

## Observações



Exemplo: 
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

Recupera um gráfico do workbook [Excel](../../../aspose.slides.excel/) especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | A coleção de formas à qual o gráfico será adicionado. |
| x | **float** | A coordenada X para posicionar o gráfico. |
| y | **float** | A coordenada Y para posicionar o gráfico. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um fluxo contendo os dados do workbook. |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha que contém o gráfico. |
| chartName | [System::String](../../../system/string/) | O nome do gráfico a ser adicionado. |
| embedAllWorkbook | **bool** | Se **true**, todo o workbook será incorporado ao gráfico; se **false**, apenas os dados do gráfico serão incorporados. |

### Valor de retorno

O gráfico que foi adicionado à coleção de formas.

## Observações



Exemplo: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method

Recupera um gráfico do workbook [Excel](../../../aspose.slides.excel/) especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | A coleção de formas à qual o gráfico será adicionado. |
| x | **float** | A coordenada X para posicionar o gráfico. |
| y | **float** | A coordenada Y para posicionar o gráfico. |
| workbookPath | [System::String](../../../system/string/) | O caminho do arquivo para o workbook que contém o gráfico. |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha que contém o gráfico. |
| chartName | [System::String](../../../system/string/) | O nome do gráfico a ser adicionado. |
| embedWorkbook | **bool** | Se **true**, o workbook será incorporado ao gráfico; se **false**, o gráfico irá linkar ao workbook externo. |

### Valor de retorno

O gráfico que foi adicionado à coleção de formas.

## Observações



Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Classe [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Classe [String](../../../system/string/)
* Classe [ExcelWorkbookImporter](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)
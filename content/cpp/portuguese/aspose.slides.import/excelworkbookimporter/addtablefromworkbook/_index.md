---
title: AddTableFromWorkbook()
second_title: Referência da API Aspose.Slides para C++
description: Recupera uma tabela do workbook Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.
type: docs
weight: 14
url: /pt/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) método

Recupera uma tabela do workbook [Excel](../../../aspose.slides.excel/) especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | A coleção de formas à qual a tabela será adicionada. |
| x | **float** | A coordenada X para posicionar a tabela. |
| y | **float** | A coordenada Y para posicionar a tabela. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | A planilha [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha que contém a tabela. |
| cellRange | [System::String](../../../system/string/) | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Valor de Retorno

A tabela que foi adicionada à coleção de formas.

## Observações




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) método

Recupera uma tabela do arquivo de workbook [Excel](../../../aspose.slides.excel/) especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | A coleção de formas à qual a tabela será adicionada. |
| x | **float** | A coordenada X para posicionar a tabela. |
| y | **float** | A coordenada Y para posicionar a tabela. |
| workbookPath | [System::String](../../../system/string/) | O caminho para o arquivo de workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha que contém a tabela. |
| cellRange | [System::String](../../../system/string/) | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Valor de Retorno

A tabela que foi adicionada à coleção de formas.

## Observações




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) método

Recupera uma tabela do arquivo de workbook [Excel](../../../aspose.slides.excel/) especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | A coleção de formas à qual a tabela será adicionada. |
| x | **float** | A coordenada X para posicionar a tabela. |
| y | **float** | A coordenada Y para posicionar a tabela. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um fluxo contendo os dados do workbook. |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha que contém a tabela. |
| cellRange | [System::String](../../../system/string/) | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Valor de Retorno

A tabela que foi adicionada à coleção de formas.

## Observações




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITable](../../../aspose.slides/itable/)
* Classe [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Classe [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Classe [String](../../../system/string/)
* Classe [ExcelWorkbookImporter](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)
---
title: AddChartFromWorkbook()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.
type: docs
weight: 1
url: /it/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) metodo


Recupera un grafico dal foglio di calcolo [Excel](../../../aspose.slides.excel/) specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collezione di forme a cui verrà aggiunto il grafico. |
| x | **float** | La coordinata X per posizionare il grafico. |
| y | **float** | La coordinata Y per posizionare il grafico. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Il workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro che contiene il grafico. |
| chartIndex | **int32_t** | L'indice basato su zero della forma grafico da inserire. Questo indice può essere ottenuto usando il metodo [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Se **true**, l'intero workbook sarà incorporato nel grafico; se **false**, verranno incorporati solo i dati del grafico. |

### Valore di ritorno

Il grafico che è stato aggiunto alla collezione di forme.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) metodo


Recupera un grafico dal foglio di calcolo [Excel](../../../aspose.slides.excel/) specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collezione di forme a cui verrà aggiunto il grafico. |
| x | **float** | La coordinata X per posizionare il grafico. |
| y | **float** | La coordinata Y per posizionare il grafico. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Il workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | [System::String](../../../system/string/) | Il nome del grafico da aggiungere. |
| embedAllWorkbook | **bool** | Se **true**, l'intero workbook sarà incorporato nel grafico; se **false**, verranno incorporati solo i dati del grafico. |

### Valore di ritorno

Il grafico che è stato aggiunto alla collezione di forme.
## Osservazioni



Esempio: 
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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) metodo


Recupera un grafico dal foglio di calcolo [Excel](../../../aspose.slides.excel/) specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collezione di forme a cui verrà aggiunto il grafico. |
| x | **float** | La coordinata X per posizionare il grafico. |
| y | **float** | La coordinata Y per posizionare il grafico. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flusso contenente i dati del workbook. |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | [System::String](../../../system/string/) | Il nome del grafico da aggiungere. |
| embedAllWorkbook | **bool** | Se **true**, l'intero workbook sarà incorporato nel grafico; se **false**, verranno incorporati solo i dati del grafico. |

### Valore di ritorno

Il grafico che è stato aggiunto alla collezione di forme.
## Osservazioni



Esempio: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) metodo


Recupera un grafico dal foglio di calcolo [Excel](../../../aspose.slides.excel/) specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collezione di forme a cui verrà aggiunto il grafico. |
| x | **float** | La coordinata X per posizionare il grafico. |
| y | **float** | La coordinata Y per posizionare il grafico. |
| workbookPath | [System::String](../../../system/string/) | Il percorso file del workbook contenente il grafico. |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | [System::String](../../../system/string/) | Il nome del grafico da aggiungere. |
| embedWorkbook | **bool** | Se **true**, il workbook sarà incorporato nel grafico; se **false**, il grafico collegherà al workbook esterno. |

### Valore di ritorno

Il grafico che è stato aggiunto alla collezione di forme.
## Osservazioni



Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Classe [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Classe [String](../../../system/string/)
* Classe [ExcelWorkbookImporter](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)
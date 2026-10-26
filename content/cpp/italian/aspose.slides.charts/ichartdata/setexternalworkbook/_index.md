---
title: SetExternalWorkbook()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta una cartella di lavoro esterna come fonte di dati per il grafico. I dati del grafico verranno aggiornati dalla cartella di lavoro di destinazione.
type: docs
weight: 196
url: /it/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) metodo

Imposta la cartella di lavoro esterna come origine dati per il grafico. [Chart](../../chart/) dati verranno aggiornati dalla cartella di lavoro di destinazione.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Percorso della cartella di lavoro di destinazione |

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) metodo

Imposta la cartella di lavoro esterna come origine dati per il grafico.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Percorso della cartella di lavoro di destinazione |
| updateChartData | **bool** | Se il valore è false, solo il percorso della cartella di lavoro verrà aggiornato. [Chart](../../chart/) i dati non saranno caricati e aggiornati dalla cartella di lavoro di destinazione. Può essere usato quando la cartella di lavoro di destinazione non esiste o non è disponibile. Se il valore è true, i dati del grafico verranno aggiornati dalla cartella di lavoro di destinazione. |

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)
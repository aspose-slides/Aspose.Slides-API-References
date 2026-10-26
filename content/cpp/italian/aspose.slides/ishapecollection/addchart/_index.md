---
title: AddChart()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme.
type: docs
weight: 27
url: /it/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metodo

Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Il tipo di grafico da aggiungere. |
| x | **float** | La coordinata x del nuovo grafico, in punti. |
| y | **float** | La coordinata y del nuovo grafico, in punti. |
| width | **float** | La larghezza del grafico, in punti. |
| height | **float** | L'altezza del grafico, in punti. |

### Valore restituito

Il nuovo [Charts::IChart](../../../aspose.slides.charts/ichart/) creato.

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metodo

Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Il tipo di grafico da aggiungere. |
| x | **float** | La coordinata x del nuovo grafico, in punti. |
| y | **float** | La coordinata y del nuovo grafico, in punti. |
| width | **float** | La larghezza del grafico, in punti. |
| height | **float** | L'altezza del grafico, in punti. |
| initWithSample | **bool** | True per inizializzare il nuovo grafico con dati di serie di esempio e impostazioni; false per creare il grafico senza serie e solo con impostazioni minime, il che rende la creazione più veloce. |

### Valore restituito

Il nuovo [Charts::IChart](../../../aspose.slides.charts/ichart/) creato.

## Vedi anche

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
---
title: InsertChart()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato.
type: docs
weight: 92
url: /it/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metodo

Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Il tipo di grafico da creare. |
| x | **float** | La coordinata x del nuovo grafico, in punti. |
| y | **float** | La coordinata y del nuovo grafico, in punti. |
| width | **float** | La larghezza del nuovo grafico, in punti. |
| height | **float** | L'altezza del nuovo grafico, in punti. |
| index | **int32_t** | L'indice basato su zero a cui inserire il nuovo grafico nella raccolta di forme. |

### Valore di ritorno

Il [Charts::IChart](../../../aspose.slides.charts/ichart/) appena creato.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metodo

Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Il tipo di grafico da creare. |
| x | **float** | La coordinata x del nuovo grafico, in punti. |
| y | **float** | La coordinata y del nuovo grafico, in punti. |
| width | **float** | La larghezza del nuovo grafico, in punti. |
| height | **float** | L'altezza del nuovo grafico, in punti. |
| index | **int32_t** | L'indice basato su zero a cui inserire il nuovo grafico nella raccolta di forme. |
| initWithSample | **bool** | True per inizializzare il nuovo grafico con dati di serie di esempio e impostazioni; false per creare il grafico senza serie e solo con impostazioni minime, il che rende la creazione più veloce. |

### Valore di ritorno

Il [Charts::IChart](../../../aspose.slides.charts/ichart/) appena creato.

## Vedi anche

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [ShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
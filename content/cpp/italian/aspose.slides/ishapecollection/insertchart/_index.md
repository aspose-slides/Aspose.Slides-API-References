---
title: InsertChart()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo diagramma, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella collezione di forme all'indice specificato.
type: docs
weight: 53
url: /it/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metodo

Crea un nuovo diagramma, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella collezione di forme all'indice specificato.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Il tipo di diagramma da creare. |
| x | **float** | La coordinata x del nuovo diagramma, in punti. |
| y | **float** | La coordinata y del nuovo diagramma, in punti. |
| width | **float** | La larghezza del nuovo diagramma, in punti. |
| height | **float** | L'altezza del nuovo diagramma, in punti. |
| index | **int32_t** | L'indice basato su zero al quale inserire il nuovo diagramma nella collezione di forme. |

### Valore di ritorno

Il [Charts::IChart](../../../aspose.slides.charts/ichart/) appena creato.

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metodo

Crea un nuovo diagramma, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella collezione di forme all'indice specificato.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Il tipo di diagramma da creare. |
| x | **float** | La coordinata x del nuovo diagramma, in punti. |
| y | **float** | La coordinata y del nuovo diagramma, in punti. |
| width | **float** | La larghezza del nuovo diagramma, in punti. |
| height | **float** | L'altezza del nuovo diagramma, in punti. |
| index | **int32_t** | L'indice basato su zero al quale inserire il nuovo diagramma nella collezione di forme. |
| initWithSample | **bool** | True per inizializzare il nuovo diagramma con dati di serie di esempio e impostazioni; false per creare il diagramma senza serie e solo con impostazioni minime, rendendo la creazione più veloce. |

### Valore di ritorno

Il [Charts::IChart](../../../aspose.slides.charts/ichart/) appena creato.

## Vedi anche

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
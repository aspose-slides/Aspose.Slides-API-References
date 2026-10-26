---
title: InsertSummaryZoomFrame()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo frame Summary Zoom e lo inserisce nella raccolta di forme all'indice specificato.
type: docs
weight: 170
url: /it/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metodo

Crea un nuovo frame Summary Zoom e lo inserisce nella raccolta di forme all'indice specificato.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il frame Summary Zoom. |
| x | **float** | La coordinata x del nuovo frame Summary Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Summary Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Summary Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Summary Zoom, in punti. |

### Valore restituito

Il [ISummaryZoomFrame](../../isummaryzoomframe/) appena creato.

## Osservazioni

Questo metodo crea un frame Summary Zoom che aggrega i collegamenti di riepilogo per tutte le sezioni della presentazione. 

Questo esempio dimostra la creazione e l'inserimento di un oggetto Summary Zoom all'indice specificato di una raccolta (supponendo che nella presentazione "Presentation.pptx" ci siano almeno due sezioni): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
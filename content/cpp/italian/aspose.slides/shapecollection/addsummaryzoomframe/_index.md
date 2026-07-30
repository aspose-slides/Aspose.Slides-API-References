---
title: AddSummaryZoomFrame()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della collezione di forme.
type: docs
weight: 157
url: /it/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) metodo

Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della collezione di forme.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame Summary Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Summary Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Summary Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Summary Zoom, in punti. |

### Valore restituito

Il nuovo [ISummaryZoomFrame](../../isummaryzoomframe/).

## Osservazioni

Questo metodo crea un nuovo Summary Zoom e inserisce una collezione di oggetti al suo interno per tutte le sezioni di questa presentazione.

Questo esempio dimostra come aggiungere un oggetto Summary Zoom alla fine di una collezione (supponendo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomFrame](../../isummaryzoomframe/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
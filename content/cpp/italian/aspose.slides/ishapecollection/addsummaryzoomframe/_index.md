---
title: AddSummaryZoomFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della collezione di forme.
type: docs
weight: 144
url: /it/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) metodo

Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della collezione di forme.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame Summary Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Summary Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Summary Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Summary Zoom, in punti. |

### Valore di ritorno

Il nuovo [ISummaryZoomFrame](../../isummaryzoomframe/) creato.

## Osservazioni

Questo metodo crea un frame Summary Zoom che aggrega i collegamenti di riepilogo per tutte le sezioni nella presentazione.

Questo esempio mostra come aggiungere un oggetto Summary Zoom alla fine di una raccolta (supponendo che nella presentazione "Presentation.pptx" vi siano almeno due sezioni):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISummaryZoomFrame](../../isummaryzoomframe/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
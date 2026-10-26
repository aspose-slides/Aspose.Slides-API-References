---
title: InsertVideoFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo fotogramma video e lo inserisce nella raccolta di forme all'indice specificato.
type: docs
weight: 183
url: /it/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) metodo

Crea un nuovo fotogramma video e lo inserisce nella raccolta di forme all'indice specificato.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il fotogramma video. |
| x | **float** | La coordinata x del nuovo fotogramma video, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma video, in punti. |
| width | **float** | La larghezza del nuovo fotogramma video, in punti. |
| height | **float** | L'altezza del nuovo fotogramma video, in punti. |
| fname | [System::String](../../../system/string/) | Il percorso o il nome del file video da incorporare. |

### Valore di ritorno

Il [IVideoFrame](../../ivideoframe/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoFrame](../../ivideoframe/)
* Classe [String](../../../system/string/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
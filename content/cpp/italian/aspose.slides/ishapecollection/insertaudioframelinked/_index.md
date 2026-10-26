---
title: InsertAudioFrameLinked()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame audio collegato a un file audio esterno e lo inserisce nella collezione di forme all'indice specificato.
type: docs
weight: 235
url: /it/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metodo

Crea un nuovo frame audio collegato a un file audio esterno e lo inserisce nella collezione di forme all'indice specificato.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il frame audio. |
| x | **float** | La coordinata x del nuovo frame audio, in punti. |
| y | **float** | La coordinata y del nuovo frame audio, in punti. |
| width | **float** | La larghezza del nuovo frame audio, in punti. |
| height | **float** | L'altezza del nuovo frame audio, in punti. |
| fname | [System::String](../../../system/string/) | Il percorso o il nome del file audio esterno da collegare. |

### Valore restituito

Il [IAudioFrame](../../iaudioframe/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
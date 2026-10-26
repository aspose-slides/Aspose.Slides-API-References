---
title: InsertAudioFrameLinked()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo fotogramma audio collegato a un file audio esterno e lo inserisce nella collezione di forme all'indice specificato.
type: docs
weight: 274
url: /it/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) method


Crea un nuovo fotogramma audio collegato a un file audio esterno e lo inserisce nella collezione di forme all'indice specificato.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Parametri

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice base zero al quale inserire il fotogramma audio. |
| x | **float** | La coordinata x del nuovo fotogramma audio, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma audio, in punti. |
| width | **float** | La larghezza del nuovo fotogramma audio, in punti. |
| height | **float** | L'altezza del nuovo fotogramma audio, in punti. |
| fname | [System::String](../../../system/string/) | Il percorso o il nome del file audio esterno da collegare. |

### Valore di ritorno

Il nuovo [IAudioFrame](../../iaudioframe/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [String](../../../system/string/)
* Classe [ShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
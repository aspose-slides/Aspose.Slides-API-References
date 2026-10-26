---
title: AddAudioFrameLinked()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo frame audio collegato a un file audio esterno e lo aggiunge alla fine della collezione di forme.
type: docs
weight: 261
url: /it/aspose.slides/shapecollection/addaudioframelinked/
---
## ShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) method

Crea un nuovo frame audio collegato a un file audio esterno e lo aggiunge alla fine della collezione di forme.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame audio, in punti. |
| y | **float** | La coordinata y del nuovo frame audio, in punti. |
| width | **float** | La larghezza del nuovo frame audio, in punti. |
| height | **float** | L'altezza del nuovo frame audio, in punti. |
| fname | [System::String](../../../system/string/) | Il percorso o il nome del file audio esterno da collegare. |

### Valore di ritorno

Il [IAudioFrame](../../iaudioframe/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
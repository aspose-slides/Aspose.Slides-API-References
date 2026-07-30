---
title: AddVideoFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo fotogramma video e lo aggiunge alla fine della raccolta di forme.
type: docs
weight: 170
url: /it/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) metodo

Crea un nuovo fotogramma video e lo aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo fotogramma video, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma video, in punti. |
| width | **float** | La larghezza del nuovo fotogramma video, in punti. |
| height | **float** | L'altezza del nuovo fotogramma video, in punti. |
| fname | [System::String](../../../system/string/) | Il percorso o il nome del file video da incorporare. |

### Valore restituito

Il [IVideoFrame](../../ivideoframe/) appena creato.

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metodo

Crea un nuovo fotogramma video e lo aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo fotogramma video, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma video, in punti. |
| width | **float** | La larghezza del nuovo fotogramma video, in punti. |
| height | **float** | L'altezza del nuovo fotogramma video, in punti. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Il [IVideo](../../ivideo/) da incorporare nel fotogramma video. |

### Valore restituito

Il [IVideoFrame](../../ivideoframe/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoFrame](../../ivideoframe/)
* Classe [String](../../../system/string/)
* Classe [IShapeCollection](../)
* Classe [IVideo](../../ivideo/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: AddVideoFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme.
type: docs
weight: 209
url: /it/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) metodo


Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame video, in punti. |
| y | **float** | La coordinata y del nuovo frame video, in punti. |
| width | **float** | La larghezza del nuovo frame video, in punti. |
| height | **float** | L’altezza del nuovo frame video, in punti. |
| fname | [System::String](../../../system/string/) | Il percorso o il nome del file video da incorporare. |

### Valore restituito

Il [IVideoFrame](../../ivideoframe/) appena creato.

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metodo


Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame video, in punti. |
| y | **float** | La coordinata y del nuovo frame video, in punti. |
| width | **float** | La larghezza del nuovo frame video, in punti. |
| height | **float** | L’altezza del nuovo frame video, in punti. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Il [IVideo](../../ivideo/) da incorporare nel frame video. |

### Valore restituito

Il [IVideoFrame](../../ivideoframe/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoFrame](../../ivideoframe/)
* Classe [String](../../../system/string/)
* Classe [ShapeCollection](../)
* Classe [IVideo](../../ivideo/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
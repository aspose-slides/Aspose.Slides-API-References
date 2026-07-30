---
title: AddOleObjectFrame()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo frame OLE e lo aggiunge alla fine della collezione di forme.
type: docs
weight: 66
url: /it/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Crea un nuovo frame OLE e lo aggiunge alla fine della collezione di forme.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Le informazioni sui dati OLE incorporati ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valore di ritorno

Il [IOleObjectFrame](../../ioleobjectframe/) appena creato.

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method


Crea un nuovo frame OLE e lo aggiunge alla fine della collezione di forme.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| className | [System::String](../../../system/string/) | Il nome della classe dell'oggetto OLE. |
| path | [System::String](../../../system/string/) | Il percorso al file collegato. |

### Valore di ritorno

Il [IOleObjectFrame](../../ioleobjectframe/) appena creato.

## Osservazioni



Questo percorso viene memorizzato così com'è nella presentazione. Se viene specificato un percorso relativo, il file non sarà accessibile aprendo la presentazione da una directory diversa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
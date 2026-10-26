---
title: InsertOleObjectFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame di oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato.
type: docs
weight: 79
url: /it/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metodo

Crea un nuovo frame di oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice base zero in cui inserire il frame dell'oggetto OLE. |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Le informazioni sui dati OLE incorporati ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valore restituito

Il [IOleObjectFrame](../../ioleobjectframe/) appena creato.

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metodo

Crea un nuovo frame di oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice base zero in cui inserire il frame dell'oggetto OLE. |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| className | [System::String](../../../system/string/) | Il nome della classe dell'oggetto OLE. |
| path | [System::String](../../../system/string/) | Il percorso del file collegato. |

### Valore restituito

Il [IOleObjectFrame](../../ioleobjectframe/) appena creato.

## Osservazioni

Questo percorso viene memorizzato così com'è nella presentazione. Se viene specificato un percorso relativo, il file sarà inaccessibile aprendo la presentazione da una directory diversa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleObjectFrame](../../ioleobjectframe/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [IShapeCollection](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
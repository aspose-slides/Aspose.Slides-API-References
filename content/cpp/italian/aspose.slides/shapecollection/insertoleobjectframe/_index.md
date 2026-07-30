---
title: InsertOleObjectFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame di oggetto OLE e lo inserisce nella collezione di forme all'indice specificato.
type: docs
weight: 196
url: /it/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metodo


Crea un nuovo frame di oggetto OLE e lo inserisce nella collezione di forme all'indice specificato.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il frame dell'oggetto OLE. |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Le informazioni sui dati OLE incorporati ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valore di ritorno

Il [IOleObjectFrame](../../ioleobjectframe/) appena creato.

## Osservazioni



Questo esempio dimostra l'inserimento di un oggetto OLE al secondo indice: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metodo


Crea un nuovo frame di oggetto OLE e lo inserisce nella collezione di forme all'indice specificato.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire il frame dell'oggetto OLE. |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| className | [System::String](../../../system/string/) | Il nome della classe dell'oggetto OLE. |
| path | [System::String](../../../system/string/) | Il percorso del file collegato. |

### Valore di ritorno

Il frame di oggetto OLE appena creato.

## Osservazioni



Questo percorso è memorizzato così com'è nella presentazione. Se viene specificato un percorso relativo, il file sarà inaccessibile quando si apre la presentazione da una directory diversa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleObjectFrame](../../ioleobjectframe/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [ShapeCollection](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
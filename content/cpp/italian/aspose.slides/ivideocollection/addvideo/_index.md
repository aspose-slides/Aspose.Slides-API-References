---
title: AddVideo()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di un file video da un'altra presentazione.
type: docs
weight: 14
url: /it/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metodo


Aggiunge una copia di un file video da un'altra presentazione.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Video di origine. |

### Valore restituito

Video aggiunto.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metodo


Crea e aggiunge un video a una presentazione dallo stream.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream da cui aggiungere il file video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Il comportamento che verrà applicato allo stream. |

### Valore restituito

Aggiunto [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metodo


Crea e aggiunge un video a una presentazione da un array di byte.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) byte. |

### Valore restituito

Video aggiunto.

## Vedi anche

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [IVideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
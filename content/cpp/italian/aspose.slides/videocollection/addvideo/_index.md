---
title: AddVideo()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di un file video da un'altra presentazione.
type: docs
weight: 53
url: /it/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metodo

Aggiunge una copia di un file video da un'altra presentazione.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Video di origine. |

### Valore restituito

Video aggiunto.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metodo

Crea e aggiunge un video a una presentazione da un flusso.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere il file video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Il comportamento che sarà applicato al flusso. |

### Valore restituito

Aggiunto [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metodo


Crea e aggiunge un video a una presentazione da un array di byte.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
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
* Class [VideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
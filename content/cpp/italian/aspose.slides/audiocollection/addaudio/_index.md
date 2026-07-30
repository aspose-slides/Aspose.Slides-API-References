---
title: AddAudio()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di un file audio da un'altra presentazione.
type: docs
weight: 53
url: /it/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metodo

Aggiunge una copia di un file audio da un'altra presentazione.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Audio di origine. |

### Valore restituito

Audio aggiunto.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metodo

Crea e aggiunge un audio a una presentazione da uno stream.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere l'audio. |

### Valore restituito

Audio aggiunto.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metodo

Crea e aggiunge un audio a una presentazione da uno stream.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere l'audio video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Il comportamento che verrà applicato al flusso. |

### Valore restituito

Audio aggiunto.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metodo

Crea e aggiunge un audio a una presentazione da un array di byte.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) byte. |

### Valore restituito

Audio aggiunto.

## Vedi anche

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IAudio](../../iaudio/)
* Classe [AudioCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
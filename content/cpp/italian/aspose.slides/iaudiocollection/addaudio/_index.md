---
title: AddAudio()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di un file audio da un'altra presentazione.
type: docs
weight: 14
url: /it/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metodo

Aggiunge una copia di un file audio da un'altra presentazione.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Audio di origine. |

### Valore di ritorno

Audio aggiunto.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metodo

Crea e aggiunge un audio a una presentazione da un flusso.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere l'audio. |

### Valore di ritorno

Audio aggiunto.

Deprecata
:   Usa AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Il metodo sarà rimosso nella versione 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metodo

Crea e aggiunge un audio a una presentazione da un flusso.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso da cui aggiungere l'audio video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Il comportamento che sarà applicato al flusso. |

### Valore di ritorno

Audio aggiunto.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metodo

Crea e aggiunge un audio a una presentazione da un array di byte.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) byte. |

### Valore di ritorno

Audio aggiunto.

## Vedi anche

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IAudio](../../iaudio/)
* Classe [IAudioCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
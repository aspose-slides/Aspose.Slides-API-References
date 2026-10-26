---
title: AddAudio()
second_title: Referencia de la API de Aspose.Slides para C++
description: Añade una copia de un archivo de audio de otra presentación.
type: docs
weight: 53
url: /es/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) método

Añade una copia de un archivo de audio de otra presentación.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Audio de origen. |

### Valor devuelto

Audio agregado.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) método

Crea y agrega un audio a una presentación desde un flujo.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo desde el cual agregar audio. |

### Valor devuelto

Audio agregado.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método

Crea y agrega un audio a una presentación desde un flujo.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo desde el cual agregar el audio de video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | El comportamiento que se aplicará al flujo. |

### Valor devuelto

Audio agregado.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) método

Crea y agrega un audio a una presentación desde una matriz de bytes.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bytes. |

### Valor devuelto

Audio agregado.

## Ver también

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IAudio](../../iaudio/)
* Clase [AudioCollection](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
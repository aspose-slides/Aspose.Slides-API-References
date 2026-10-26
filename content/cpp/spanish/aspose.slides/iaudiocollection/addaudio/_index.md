---
title: AddAudio()
second_title: Referencia de API de Aspose.Slides para C++
description: Añade una copia de un archivo de audio de otra presentación.
type: docs
weight: 14
url: /es/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) método


Añade una copia de un archivo de audio de otra presentación.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Audio de origen. |

### Valor devuelto

Audio añadido.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) método


Crea y agrega un audio a una presentación desde un flujo.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo del cual agregar el audio. |

### Valor devuelto

Audio añadido.

Obsoleto:
   Use AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). El método será eliminado en la versión 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método


Crea y agrega un audio a una presentación desde un flujo.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo del cual agregar el audio del video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | El comportamiento que se aplicará al flujo. |

### Valor devuelto

Audio añadido.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) método


Crea y agrega un audio a una presentación desde una matriz de bytes.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bytes. |

### Valor devuelto

Audio añadido.

## Ver también

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IAudio](../../iaudio/)
* Clase [IAudioCollection](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
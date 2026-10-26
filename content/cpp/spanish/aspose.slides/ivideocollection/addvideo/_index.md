---
title: AddVideo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una copia de un archivo de video de otra presentación.
type: docs
weight: 14
url: /es/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) método

Agrega una copia de un archivo de video de otra presentación.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Video de origen. |

### Valor devuelto

Video añadido.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método

Crea y agrega un video a una presentación desde un flujo.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo del cual se agrega el archivo de video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | El comportamiento que se aplicará al flujo. |

### Valor devuelto

Añadido [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) método

Crea y agrega un video a una presentación a partir de un arreglo de bytes.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bytes. |

### Valor devuelto

Video añadido.

## Ver también

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IVideo](../../ivideo/)
* Clase [IVideoCollection](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
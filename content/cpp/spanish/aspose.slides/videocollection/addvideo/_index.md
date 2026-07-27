---
title: AddVideo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Añade una copia de un archivo de video de otra presentación.
type: docs
weight: 53
url: /es/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) método


Añade una copia de un archivo de video de otra presentación.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Video de origen. |

### Valor devuelto

Video añadido.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método


Crea y agrega un video a una presentación a partir de un flujo.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo del cual agregar el archivo de video. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | El comportamiento que se aplicará al flujo. |

### Valor devuelto

Añadido [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) método


Crea y agrega un video a una presentación a partir de un arreglo de bytes.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bytes. |

### Valor devuelto

Video añadido.

## Ver también

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IVideo](../../ivideo/)
* Clase [VideoCollection](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
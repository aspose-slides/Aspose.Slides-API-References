---
title: ReadPresentation()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee una presentación existente desde un array
type: docs
weight: 27
url: /es/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) método


Lee una presentación existente desde un array

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array para leer |

### Valor devuelto

Presentación leída

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) método


Lee una presentación existente desde un array con opciones de carga adicionales

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array para leer |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opciones de carga |

### Valor devuelto

Presentación leída

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) método


Lee una presentación existente desde un flujo

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de entrada para leer |

### Valor devuelto

Presentación leída

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) método


Lee una presentación existente desde un flujo con opciones de carga adicionales

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de entrada para leer |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opciones de carga |

### Valor devuelto

Presentación leída

## IPresentationFactory::ReadPresentation(System::String) método


Lee una presentación existente desde un archivo

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nombre de archivo |

### Valor devuelto

Presentación leída

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) método


Lee una presentación existente desde un archivo con opciones de carga adicionales

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nombre de archivo |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opciones de carga |

### Valor devuelto

Presentación leída

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IPresentation](../../ipresentation/)
* Clase [IPresentationFactory](../)
* Clase [ILoadOptions](../../iloadoptions/)
* Clase [Stream](../../../system.io/stream/)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
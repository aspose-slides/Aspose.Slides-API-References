---
title: ReadPresentation()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee una presentación existente desde un array
type: docs
weight: 40
url: /es/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) método


Lee una presentación existente desde un array

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array to read |

### Valor devuelto

Presentación leída

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) método


Lee una presentación existente desde un array con opciones de carga adicionales

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array to read |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Valor devuelto

Presentación leída

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) método


Lee una presentación existente desde un flujo

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de entrada para leer |

### Valor devuelto

Presentación leída

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) método


Lee una presentación existente desde un flujo con opciones de carga adicionales

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de entrada para leer |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Valor devuelto

Presentación leída

## PresentationFactory::ReadPresentation(System::String) método


Lee una presentación existente desde un archivo

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nombre del archivo |

### Valor devuelto

Presentación leída

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) método


Lee una presentación existente desde un archivo con opciones de carga adicionales

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nombre del archivo |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Valor devuelto

Presentación leída

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IPresentation](../../ipresentation/)
* Clase [PresentationFactory](../)
* Clase [ILoadOptions](../../iloadoptions/)
* Clase [Stream](../../../system.io/stream/)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
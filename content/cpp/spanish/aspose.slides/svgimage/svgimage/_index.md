---
title: SvgImage()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo objeto SvgImage.
type: docs
weight: 53
url: /es/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) constructor

Crea un nuevo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datos Svg. |

## SvgImage::SvgImage(System::String) constructor

Crea un nuevo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Contenido Svg. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) constructor

Crea un nuevo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo Svg. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Crea un nuevo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datos Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| baseUri | [System::String](../../../system/string/) | URI base del Svg especificado. Utilizado para resolver enlaces relativos. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Crea un nuevo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Contenido Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| baseUri | [System::String](../../../system/string/) | URI base del Svg especificado. Utilizado para resolver enlaces relativos. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Crea un nuevo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| baseUri | [System::String](../../../system/string/) | URI base del Svg especificado. Utilizado para resolver enlaces relativos. |

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
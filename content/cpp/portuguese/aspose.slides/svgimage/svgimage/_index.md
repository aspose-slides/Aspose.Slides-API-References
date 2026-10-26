---
title: SvgImage()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo objeto SvgImage.
type: docs
weight: 53
url: /pt/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) construtor

Cria novo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dados SVG. |

## SvgImage::SvgImage(System::String) construtor

Cria novo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Conteúdo SVG. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) construtor

Cria novo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo SVG. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) construtor

Cria novo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dados SVG. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| baseUri | [System::String](../../../system/string/) | URI base do SVG especificado. Usado para resolver links relativos. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) construtor

Cria novo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Conteúdo SVG. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| baseUri | [System::String](../../../system/string/) | URI base do SVG especificado. Usado para resolver links relativos. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) construtor

Cria novo objeto [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo SVG. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| baseUri | [System::String](../../../system/string/) | URI base do SVG especificado. Usado para resolver links relativos. |

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
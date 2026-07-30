---
title: SvgImage()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový objekt SvgImage.
type: docs
weight: 53
url: /cs/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) konstruktor


Vytvoří nový objekt [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data SVG. |

## SvgImage::SvgImage(System::String) konstruktor


Vytvoří nový objekt [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Obsah SVG. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) konstruktor


Vytvoří nový objekt [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream SVG. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Vytvoří nový objekt [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data SVG. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný pro načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | [System::String](../../../system/string/) | Základní URI zadaného SVG. Používá se k řešení relativních odkazů. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Vytvoří nový objekt [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Obsah SVG. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný pro načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | [System::String](../../../system/string/) | Základní URI zadaného SVG. Používá se k řešení relativních odkazů. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Vytvoří nový objekt [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream SVG. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný pro načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | [System::String](../../../system/string/) | Základní URI zadaného SVG. Používá se k řešení relativních odkazů. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [SvgImage](../)
* Třída [String](../../../system/string/)
* Třída [Stream](../../../system.io/stream/)
* Třída [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
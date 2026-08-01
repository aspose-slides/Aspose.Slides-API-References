---
title: SvgImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert een nieuw SvgImage-object.
type: docs
weight: 53
url: /nl/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) constructor

Creëert een nieuw [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg-gegevens. |

## SvgImage::SvgImage(System::String) constructor

Creëert een nieuw [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg-inhoud. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) constructor

Creëert een nieuw [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg-stream. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Creëert een nieuw [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg-gegevens. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| baseUri | [System::String](../../../system/string/) | Basis-URI van de opgegeven Svg. Wordt gebruikt om relatieve koppelingen op te lossen. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Creëert een nieuw [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg-inhoud. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| baseUri | [System::String](../../../system/string/) | Basis-URI van de opgegeven Svg. Wordt gebruikt om relatieve koppelingen op te lossen. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Creëert een nieuw [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg-stream. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| baseUri | [System::String](../../../system/string/) | Basis-URI van de opgegeven Svg. Wordt gebruikt om relatieve koppelingen op te lossen. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
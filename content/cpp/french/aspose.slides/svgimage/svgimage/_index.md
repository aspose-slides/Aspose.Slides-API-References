---
title: SvgImage()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouvel objet SvgImage.
type: docs
weight: 53
url: /fr/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) constructeur


Crée un nouvel objet [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Données Svg. |

## SvgImage::SvgImage(System::String) constructeur


Crée un nouvel objet [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Contenu Svg. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) constructeur


Crée un nouvel objet [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux Svg. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructeur


Crée un nouvel objet [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Données Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| baseUri | [System::String](../../../system/string/) | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructeur


Crée un nouvel objet [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Contenu Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| baseUri | [System::String](../../../system/string/) | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructeur


Crée un nouvel objet [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| baseUri | [System::String](../../../system/string/) | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
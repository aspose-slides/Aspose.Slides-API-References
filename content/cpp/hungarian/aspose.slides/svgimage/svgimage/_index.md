---
title: SvgImage()
second_title: Aspose.Slides C++ API-referencia
description: Új SvgImage objektumot hoz létre.
type: docs
weight: 53
url: /hu/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) konstruktor


Új [SvgImage](../) objektumot hoz létre.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg adat. |

## SvgImage::SvgImage(System::String) konstruktor


Új [SvgImage](../) objektumot hoz létre.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg tartalom. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) konstruktor


Új [SvgImage](../) objektumot hoz létre.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg adatfolyam. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Új [SvgImage](../) objektumot hoz létre.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg adat. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amelyet külső objektumok lekérésére használnak. Ha ez a paraméter null, minden külső objektum figyelmen kívül lesz hagyva. |
| baseUri | [System::String](../../../system/string/) | A megadott Svg alap URI-je. Relatív hivatkozások feloldásához használja. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Új [SvgImage](../) objektumot hoz létre.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg tartalom. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amelyet külső objektumok lekérésére használnak. Ha ez a paraméter null, minden külső objektum figyelmen kívül lesz hagyva. |
| baseUri | [System::String](../../../system/string/) | A megadott Svg alap URI-je. Relatív hivatkozások feloldásához használja. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Új [SvgImage](../) objektumot hoz létre.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg adatfolyam. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amelyet külső objektumok lekérésére használnak. Ha ez a paraméter null, minden külső objektum figyelmen kívül lesz hagyva. |
| baseUri | [System::String](../../../system/string/) | A megadott Svg alap URI-je. Relatív hivatkozások feloldásához használja. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
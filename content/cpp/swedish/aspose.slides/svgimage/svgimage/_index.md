---
title: SvgImage()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt SvgImage-objekt.
type: docs
weight: 53
url: /sv/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) konstruktor


Skapar ett nytt [SvgImage](../)-objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg-data. |

## SvgImage::SvgImage(System::String) konstruktor


Skapar ett nytt [SvgImage](../)-objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg-innehåll. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) konstruktor


Skapar ett nytt [SvgImage](../)-objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg-ström. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Skapar ett nytt [SvgImage](../)-objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg-data. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null ignoreras alla externa objekt. |
| baseUri | [System::String](../../../system/string/) | Bas-URI för den angivna Svg. Används för att lösa relativa länkar. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Skapar ett nytt [SvgImage](../)-objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg-innehåll. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null ignoreras alla externa objekt. |
| baseUri | [System::String](../../../system/string/) | Bas-URI för den angivna Svg. Används för att lösa relativa länkar. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor


Skapar ett nytt [SvgImage](../)-objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg-ström. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null ignoreras alla externa objekt. |
| baseUri | [System::String](../../../system/string/) | Bas-URI för den angivna Svg. Används för att lösa relativa länkar. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [SvgImage](../)
* Klass [String](../../../system/string/)
* Klass [Stream](../../../system.io/stream/)
* Klass [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
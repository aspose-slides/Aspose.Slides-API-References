---
title: SvgImage()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues SvgImage-Objekt.
type: docs
weight: 53
url: /de/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) Konstruktor

Erstellt ein neues [SvgImage](../)-Objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg-Daten. |

## SvgImage::SvgImage(System::String) Konstruktor

Erstellt ein neues [SvgImage](../)-Objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg-Inhalt. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) Konstruktor

Erstellt ein neues [SvgImage](../)-Objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg-Stream. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Konstruktor

Erstellt ein neues [SvgImage](../)-Objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg-Daten. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| baseUri | [System::String](../../../system/string/) | Basis-URI des angegebenen Svg. Wird zum Auflösen relativer Links verwendet. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Konstruktor

Erstellt ein neues [SvgImage](../)-Objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg-Inhalt. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| baseUri | [System::String](../../../system/string/) | Basis-URI des angegebenen Svg. Wird zum Auflösen relativer Links verwendet. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Konstruktor

Erstellt ein neues [SvgImage](../)-Objekt.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg-Stream. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| baseUri | [System::String](../../../system/string/) | Basis-URI des angegebenen Svg. Wird zum Auflösen relativer Links verwendet. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SvgImage](../)
* Klasse [String](../../../system/string/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)
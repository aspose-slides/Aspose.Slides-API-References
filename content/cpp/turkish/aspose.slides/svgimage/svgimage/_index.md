---
title: SvgImage()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir SvgImage nesnesi oluşturur.
type: docs
weight: 53
url: /tr/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) constructor

Yeni bir [SvgImage](../) nesnesi oluşturur.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg verisi. |

## SvgImage::SvgImage(System::String) constructor

Yeni bir [SvgImage](../) nesnesi oluşturur.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg içeriği. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) constructor

Yeni bir [SvgImage](../) nesnesi oluşturur.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg akışı. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Yeni bir [SvgImage](../) nesnesi oluşturur.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg verisi. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| baseUri | [System::String](../../../system/string/) | Belirtilen Svg’nin temel URI’si. Göreli bağlantıların çözülmesinde kullanılır. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Yeni bir [SvgImage](../) nesnesi oluşturur.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg içeriği. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| baseUri | [System::String](../../../system/string/) | Belirtilen Svg’nin temel URI’si. Göreli bağlantıların çözülmesinde kullanılır. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

Yeni bir [SvgImage](../) nesnesi oluşturur.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg akışı. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| baseUri | [System::String](../../../system/string/) | Belirtilen Svg’nin temel URI’si. Göreli bağlantıların çözülmesinde kullanılır. |

## Diğerlerine Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
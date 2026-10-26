---
title: SvgImage()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek SvgImage baru.
type: docs
weight: 53
url: /id/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) konstruktor

Membuat objek [SvgImage](../) baru.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data Svg. |

## SvgImage::SvgImage(System::String) konstruktor

Membuat objek [SvgImage](../) baru.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Konten Svg. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) konstruktor

Membuat objek [SvgImage](../) baru.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream Svg. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor

Membuat objek [SvgImage](../) baru.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | [System::String](../../../system/string/) | URI dasar dari Svg yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor

Membuat objek [SvgImage](../) baru.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Konten Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | [System::String](../../../system/string/) | URI dasar dari Svg yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) konstruktor

Membuat objek [SvgImage](../) baru.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | [System::String](../../../system/string/) | URI dasar dari Svg yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
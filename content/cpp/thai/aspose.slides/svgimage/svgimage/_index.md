---
title: SvgImage()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอ็อบเจกต์ SvgImage ใหม่.
type: docs
weight: 53
url: /th/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) constructor

สร้างอ็อบเจกต์ [SvgImage](../) ใหม่.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูล Svg. |

## SvgImage::SvgImage(System::String) constructor

สร้างอ็อบเจกต์ [SvgImage](../) ใหม่.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | เนื้อหา Svg. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) constructor

สร้างอ็อบเจกต์ [SvgImage](../) ใหม่.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีม Svg. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

สร้างอ็อบเจกต์ [SvgImage](../) ใหม่.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูล Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจกต์ callback ที่ใช้ดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| baseUri | [System::String](../../../system/string/) | URI ฐานของ Svg ที่ระบุ ใช้เพื่อแก้ลิงก์เชิงสัมพันธ์. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

สร้างอ็อบเจกต์ [SvgImage](../) ใหม่.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | เนื้อหา Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจกต์ callback ที่ใช้ดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| baseUri | [System::String](../../../system/string/) | URI ฐานของ Svg ที่ระบุ ใช้เพื่อแก้ลิงก์เชิงสัมพันธ์. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor

สร้างอ็อบเจกต์ [SvgImage](../) ใหม่.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีม Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจกต์ callback ที่ใช้ดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| baseUri | [System::String](../../../system/string/) | URI ฐานของ Svg ที่ระบุ ใช้เพื่อแก้ลิงก์เชิงสัมพันธ์. |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
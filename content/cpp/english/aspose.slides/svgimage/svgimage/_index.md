---
title: SvgImage()
second_title: Aspose.Slides for C++ API Reference
description: Creates new SvgImage object.
type: docs
weight: 53
url: /aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) constructor


Creates new [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg data. |

## SvgImage::SvgImage(System::String) constructor


Creates new [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg content. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) constructor


Creates new [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg stream. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor


Creates new [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg data. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [System::String](../../../system/string/) | Base URI of the specified Svg. Used to resolve relative links. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor


Creates new [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg content. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [System::String](../../../system/string/) | Base URI of the specified Svg. Used to resolve relative links. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) constructor


Creates new [SvgImage](../) object.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg stream. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [System::String](../../../system/string/) | Base URI of the specified Svg. Used to resolve relative links. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
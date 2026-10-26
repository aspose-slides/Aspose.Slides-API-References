---
title: SvgImage()
second_title: Aspose.Slides for C++ API 参考
description: 创建新的 SvgImage 对象。
type: docs
weight: 53
url: /zh/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) 构造函数

创建新的[SvgImage](../)对象。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg 数据。 |

## SvgImage::SvgImage(System::String) 构造函数

创建新的[SvgImage](../)对象。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg 内容。 |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) 构造函数

创建新的[SvgImage](../)对象。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg 流。 |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 构造函数

创建新的[SvgImage](../)对象。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg 数据。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则会忽略所有外部对象。 |
| baseUri | [System::String](../../../system/string/) | 指定 Svg 的基础 URI。用于解析相对链接。 |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 构造函数

创建新的[SvgImage](../)对象。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg 内容。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则会忽略所有外部对象。 |
| baseUri | [System::String](../../../system/string/) | 指定 Svg 的基础 URI。用于解析相对链接。 |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 构造函数

创建新的[SvgImage](../)对象。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg 流。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用于获取外部对象的回调对象。如果此参数为 null，则会忽略所有外部对象。 |
| baseUri | [System::String](../../../system/string/) | 指定 Svg 的基础 URI。用于解析相对链接。 |

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
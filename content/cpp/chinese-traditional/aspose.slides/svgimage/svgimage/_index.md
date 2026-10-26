---
title: SvgImage()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的 SvgImage 物件。
type: docs
weight: 53
url: /zh-hant/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) 建構函式

建立新的 [SvgImage](../) 物件。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg 資料。 |

## SvgImage::SvgImage(System::String) 建構函式

建立新的 [SvgImage](../) 物件。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg 內容。 |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) 建構函式

建立新的 [SvgImage](../) 物件。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg 串流。 |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 建構函式

建立新的 [SvgImage](../) 物件。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg 資料。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，所有外部物件都會被忽略。 |
| baseUri | [System::String](../../../system/string/) | 指定 Svg 的基礎 URI。用於解析相對連結。 |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 建構函式

建立新的 [SvgImage](../) 物件。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg 內容。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，所有外部物件都會被忽略。 |
| baseUri | [System::String](../../../system/string/) | 指定 Svg 的基礎 URI。用於解析相對連結。 |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 建構函式

建立新的 [SvgImage](../) 物件。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg 串流。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 用於取得外部物件的回呼物件。如果此參數為 null，所有外部物件都會被忽略。 |
| baseUri | [System::String](../../../system/string/) | 指定 Svg 的基礎 URI。用於解析相對連結。 |

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [SvgImage](../)
* 類別 [String](../../../system/string/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
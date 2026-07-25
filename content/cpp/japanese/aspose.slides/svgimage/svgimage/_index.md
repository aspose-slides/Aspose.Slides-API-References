---
title: SvgImage()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい SvgImage オブジェクトを作成します。
type: docs
weight: 53
url: /ja/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) コンストラクタ

[SvgImage](../) オブジェクトを作成します。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg データ。 |

## SvgImage::SvgImage(System::String) コンストラクタ

[SvgImage](../) オブジェクトを作成します。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg コンテンツ。 |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) コンストラクタ

[SvgImage](../) オブジェクトを作成します。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg ストリーム。 |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) コンストラクタ

[SvgImage](../) オブジェクトを作成します。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg データ。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクトです。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| baseUri | [System::String](../../../system/string/) | 指定された Svg のベース URI。相対リンクの解決に使用されます。 |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) コンストラクタ

[SvgImage](../) オブジェクトを作成します。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg コンテンツ。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクトです。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| baseUri | [System::String](../../../system/string/) | 指定された Svg のベース URI。相対リンクの解決に使用されます。 |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) コンストラクタ

[SvgImage](../) オブジェクトを作成します。

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg ストリーム。 |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクトです。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| baseUri | [System::String](../../../system/string/) | 指定された Svg のベース URI。相対リンクの解決に使用されます。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [SvgImage](../)
* クラス [String](../../../system/string/)
* クラス [Stream](../../../system.io/stream/)
* クラス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
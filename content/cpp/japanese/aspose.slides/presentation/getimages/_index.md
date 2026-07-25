---
title: GetImages()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのすべてのスライドの Image オブジェクトを返します。
type: docs
weight: 456
url: /ja/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) メソッド

プレゼンテーションのすべてのスライドの Image オブジェクトを返します。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff オプション。 |

### 戻り値

Image オブジェクト。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) メソッド

プレゼンテーションの指定されたスライドの Thumbnail Image オブジェクトを返します。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff オプション。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | スライドの位置を含む配列（1 から開始）。 |

### 戻り値

Image オブジェクト。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) メソッド

カスタムスケーリングでプレゼンテーションのすべてのスライドの Thumbnail Image オブジェクトを返します。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff オプション。 |
| scaleX | **float** | x 軸方向にこのサムネイルを拡大縮小する値。 |
| scaleY | **float** | y 軸方向にこのサムネイルを拡大縮小する値。 |

### 戻り値

Image オブジェクト。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) メソッド

カスタムスケーリングでプレゼンテーションの指定されたスライドの Thumbnail Image オブジェクトを返します。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff オプション。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | スライドの位置を含む配列（1 から開始）。 |
| scaleX | **float** | x 軸方向にこのサムネイルを拡大縮小する値。 |
| scaleY | **float** | y 軸方向にこのサムネイルを拡大縮小する値。 |

### 戻り値

Image オブジェクト。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) メソッド

指定サイズでプレゼンテーションのすべてのスライドの Thumbnail Image オブジェクトを返します。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff オプション。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズ。 |

### 戻り値

Image オブジェクト。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) メソッド

指定サイズでプレゼンテーションの指定されたスライドの Thumbnail Image オブジェクトを返します。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff オプション。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | スライドの位置を含む配列（1 から開始）。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズ。 |

### 戻り値

Image オブジェクト。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IImage](../../iimage/)
* クラス [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* クラス [Presentation](../)
* クラス [Size](../../../system.drawing/size/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
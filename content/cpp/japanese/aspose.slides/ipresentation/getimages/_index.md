---
title: GetImages()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。
type: docs
weight: 417
url: /ja/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) メソッド


プレゼンテーションのすべてのスライドの Thumbnail Image オブジェクトを返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |

### 戻り値

Bitmap オブジェクト。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) メソッド


プレゼンテーションの指定されたスライドの Thumbnail Bitmap オブジェクトを返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | スライド位置の配列。1 から始まります。 |

### 戻り値

Bitmap オブジェクト。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) メソッド


カスタムスケーリングでプレゼンテーションのすべてのスライドの Thumbnail Image オブジェクトを返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |
| scaleX | **float** | この Thumbnail を x 軸方向に拡大縮小する値。 |
| scaleY | **float** | この Thumbnail を y 軸方向に拡大縮小する値。 |

### 戻り値

Bitmap オブジェクト。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) メソッド


カスタムスケーリングでプレゼンテーションの指定されたスライドの Thumbnail Image オブジェクトを返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | スライド位置の配列。1 から始まります。 |
| scaleX | **float** | この Thumbnail を x 軸方向に拡大縮小する値。 |
| scaleY | **float** | この Thumbnail を y 軸方向に拡大縮小する値。 |

### 戻り値

Bitmap オブジェクト。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) メソッド


指定されたサイズでプレゼンテーションのすべてのスライドの Thumbnail Image オブジェクトを返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズ。 |

### 戻り値

Bitmap オブジェクト。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) メソッド


指定されたサイズでプレゼンテーションの指定されたスライドの Thumbnail Image オブジェクトを返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | スライド位置の配列。1 から始まります。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズ。 |

### 戻り値

Bitmap オブジェクト。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
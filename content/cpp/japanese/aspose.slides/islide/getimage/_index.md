---
title: GetImage()
second_title: Aspose.Slides for C++ API リファレンス
description: カスタム スケーリングで画像オブジェクトを返します。
type: docs
weight: 105
url: /ja/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) メソッド

カスタム スケーリングで画像オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scaleX | **float** | このサムネイルを x 軸方向に拡大する値。 |
| scaleY | **float** | このサムネイルを y 軸方向に拡大する値。 |

### 戻り値

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() メソッド

実サイズの 20% のサムネイル Image オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### 戻り値

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) メソッド

指定したサイズの画像オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズ。 |

### 戻り値

Bitmap object.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) メソッド

指定したパラメータでサムネイル tiff ビットマップオブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff のオプション。 |

### 戻り値

Image object.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) メソッド

サムネイル Bitmap オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |

### 戻り値

Bitmap objects.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) メソッド

カスタム スケーリングでサムネイル Bitmap オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |
| scaleX | **float** | このサムネイルを x 軸方向に拡大する値。 |
| scaleY | **float** | このサムネイルを y 軸方向に拡大する値。 |

### 戻り値

Bitmap objects.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) メソッド

指定したサイズのサムネイル Bitmap オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズ。 |

### 戻り値

Bitmap objects.

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
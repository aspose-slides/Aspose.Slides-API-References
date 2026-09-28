---
title: GetImage()
second_title: Aspose.Slides for C++ API リファレンス
description: カスタムスケーリングされた画像オブジェクトを返します。
type: docs
weight: 105
url: /ja/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) メソッド

カスタムスケーリングされた画像オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleX | **float** | x 軸方向にこの Thumbnail を拡大縮小するための値です。 |
| scaleY | **float** | y 軸方向にこの Thumbnail を拡大縮小するための値です。 |

### 戻り値

Image オブジェクト [IImage](../../iimage/)

## ISlide::GetImage() メソッド

実サイズの 20% のサムネイル Image オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### 戻り値

Image オブジェクト [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) メソッド

指定されたサイズの画像オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズです。 |

### 戻り値

Image オブジェクト [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) メソッド

指定されたパラメーターでサムネイル TIFF ビットマップオブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | TIFF オプションです。 |

### 戻り値

Image オブジェクト [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) メソッド

サムネイル Bitmap オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプションです。 |

### 戻り値

Image オブジェクト [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) メソッド

カスタムスケーリングされたサムネイル Bitmap オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプションです。 |
| scaleX | **float** | x 軸方向にこの Thumbnail を拡大縮小するための値です。 |
| scaleY | **float** | y 軸方向にこの Thumbnail を拡大縮小するための値です。 |

### 戻り値

Image オブジェクト [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) メソッド

指定されたサイズのサムネイル Bitmap オブジェクトを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプションです。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズです。 |

### 戻り値

Image オブジェクト [IImage](../../iimage/)

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
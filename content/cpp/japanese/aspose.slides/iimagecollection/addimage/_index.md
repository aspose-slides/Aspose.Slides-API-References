---
title: AddImage()
second_title: C++ 用 Aspose.Slides API リファレンス
description: プレゼンテーションに画像を追加します。
type: docs
weight: 14
url: /ja/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) メソッド

プレゼンテーションに画像を追加します。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | 追加する画像。 |

### 戻り値

追加された画像。

## 備考

このメソッドは、WMF/EMF メタファイルをラスタ PNG 画像に変換してからプレゼンテーションに挿入します。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) メソッド

メモリ ストリームから画像を追加します。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | メモリ ストリーム。 |

### 戻り値

追加された画像。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) メソッド

ストリームからプレゼンテーションに画像を追加します。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 画像を追加するストリーム。 |

### 戻り値

追加された画像。

## 備考

このメソッドは、WMF/EMF メタファイルをラスタ PNG 画像に変換せずにプレゼンテーションに追加できます。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) メソッド

ストリームから画像を作成し、プレゼンテーションに追加します。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 画像ファイルを追加するストリーム。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | ストリームに適用される動作。 |

### 戻り値

追加された [IPPImage](../../ippimage/)。

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) メソッド

指定されたバッファからプレゼンテーションに画像を追加します。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バッファ。 |

### 戻り値

追加された画像。

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) メソッド

別のプレゼンテーションから画像のコピーを追加します。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 元画像。 |

### 戻り値

追加された画像。

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) メソッド

SVG オブジェクトからプレゼンテーションに画像を追加します。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG 画像オブジェクト [ISvgImage](../../isvgimage/) |

### 戻り値

追加された画像。

## 関連項目

* 列挙体 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IPPImage](../../ippimage/)
* クラス [IImage](../../iimage/)
* クラス [IImageCollection](../)
* クラス [MemoryStream](../../../system.io/memorystream/)
* クラス [Stream](../../../system.io/stream/)
* クラス [ISvgImage](../../isvgimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
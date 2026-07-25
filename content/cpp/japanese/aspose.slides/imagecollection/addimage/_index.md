---
title: AddImage()
second_title: Aspose.Slides for C++ API リファレンス
description: 別のプレゼンテーションから画像のコピーを追加します。
type: docs
weight: 53
url: /ja/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) メソッド


別のプレゼンテーションから画像のコピーを追加します。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Source image. |

### 戻り値

Added image.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) メソッド


プレゼンテーションに画像を追加します。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Image to add. |

### 戻り値

Added image.

## 備考


このメソッドは、プレゼンテーションに挿入する前に WMF/EMF メタファイルをラスター PNG 画像に変換します。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) メソッド


ストリームからプレゼンテーションに画像を追加します。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Stream to add image from. |

### 戻り値

Added image.

## 備考


このメソッドは、WMF/EMF メタファイルをラスター PNG 画像に変換せずにプレゼンテーションに追加できます。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) メソッド


ストリームからプレゼンテーションに画像を追加します。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add image from. |

### 戻り値

Added image.

## 備考


このメソッドは、WMF/EMF メタファイルをラスター PNG 画像に変換せずにプレゼンテーションに追加できます。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) メソッド


ストリームからプレゼンテーションに画像を作成し、追加します。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add image file from. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | The behavior which will be applied to the stream. |

### 戻り値

Added [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) メソッド


指定されたバッファからプレゼンテーションに画像を追加します。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### 戻り値

Added image.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) メソッド


Svg オブジェクトからプレゼンテーションに画像を追加します。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg image object [ISvgImage](../../isvgimage/) |

### 戻り値

Added image.

## 参照

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [IPPImage](../../ippimage/)
* クラス [ImageCollection](../)
* クラス [IImage](../../iimage/)
* クラス [MemoryStream](../../../system.io/memorystream/)
* クラス [Stream](../../../system.io/stream/)
* クラス [ISvgImage](../../isvgimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
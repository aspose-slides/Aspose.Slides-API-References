---
title: Save()
second_title: Aspose.Slides for C++ API リファレンス
description: 画像をファイルに保存します。
type: docs
weight: 40
url: /ja/aspose.slides/iimage/save/
---
## IImage::Save(System::String) メソッド


画像をファイルに保存します。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 画像が保存されるファイルへのパスです。 |

## IImage::Save(System::String, ImageFormat) メソッド


画像を指定された形式でファイルに保存します。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 画像が保存されるファイルへのパスです。 |
| format | [ImageFormat](../../imageformat/) | 画像形式です。 |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) メソッド


画像を指定された形式でストリームに保存します。

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 画像が保存されるストリームです。 |
| format | [ImageFormat](../../imageformat/) | 画像形式です。 |

## IImage::Save(System::String, ImageFormat, int32_t) メソッド


画像を指定された形式と品質でファイルに保存します。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 画像が保存されるファイルへのパスです。 |
| format | [ImageFormat](../../imageformat/) | 画像形式です。 |
| quality | **int32_t** | 保存された画像の品質 (0 から 100)。  

 このパラメーターは [ImageFormat::Jpeg](../../imageformat/) での保存時のみ影響し、他のすべてのフォーマットでは無視されます。 |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) メソッド


画像を指定された形式と品質でストリームに保存します。

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 画像が保存されるストリームです。 |
| format | [ImageFormat](../../imageformat/) | 画像形式です。 |
| quality | **int32_t** | 保存された画像の品質 (0 から 100)。  

 このパラメーターは [ImageFormat::Jpeg](../../imageformat/) での保存時のみ影響し、他のすべてのフォーマットでは無視されます。 |

## 参照

* 列挙体 [ImageFormat](../../imageformat/)
* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [IImage](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
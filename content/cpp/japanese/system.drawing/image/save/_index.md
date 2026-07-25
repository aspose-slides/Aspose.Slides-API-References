---
title: Save()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す画像を PNG 形式で指定されたファイルに保存します。
type: docs
weight: 1
url: /ja/system.drawing/image/save/
---
## Image::Save(const String\&) メソッド

現在のオブジェクトが表す画像を PNG 形式で指定されたファイルに保存します。

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 画像を保存するファイル名 |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) メソッド

現在のオブジェクトが表す画像を指定された形式で指定されたファイルに保存します。

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 画像を保存するファイル名 |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | 画像を保存する形式 |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) メソッド

現在のオブジェクトが表す画像を指定された形式で指定されたストリームに保存します。

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 画像を保存するストリーム |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | 画像を保存する形式 |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) メソッド

現在のオブジェクトが表す画像を、指定されたエンコーダーとエンコーダーパラメータを使用して指定されたファイルに保存します。

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 画像を保存するファイル名 |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | 使用するエンコーダー |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 使用するエンコーダーのパラメータ |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) メソッド

現在のオブジェクトが表す画像を、指定されたエンコーダーとエンコーダーパラメータを使用して指定されたストリームに保存します。

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 画像を保存するストリーム |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | 使用するエンコーダー |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 使用するエンコーダーのパラメータ |

## 参照

* 型定義 [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* 型定義 [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* クラス [String](../../../system/string/)
* クラス [Image](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)
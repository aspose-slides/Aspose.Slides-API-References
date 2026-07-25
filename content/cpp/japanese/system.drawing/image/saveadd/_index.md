---
title: SaveAdd()
second_title: Aspose.Slides for C++ API リファレンス
description: 以前の Save() メソッド呼び出しで指定されたファイルまたはストリームにフレームを追加します。
type: docs
weight: 14
url: /ja/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) メソッド

[Save()](../save/) メソッドへの前回の呼び出しで指定されたファイルまたはストリームにフレームを追加します。

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 使用するエンコーダーのパラメータ |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) メソッド

[Save()](../save/) メソッドへの前回の呼び出しで指定されたファイルまたはストリームにフレームを追加します。

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | 追加されるフレームを含む [Image](../) オブジェクト |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 使用するエンコーダーのパラメータ |

## 参照

* 型定義 [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Image](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)
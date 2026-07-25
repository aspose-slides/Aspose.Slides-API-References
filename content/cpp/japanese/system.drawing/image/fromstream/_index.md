---
title: FromStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリームから Image オブジェクトを作成します。
type: docs
weight: 339
url: /ja/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) メソッド

指定されたストリームから[Image](../)オブジェクトを作成します。

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 画像データを含むストリーム |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### 戻り値

作成された[Image](../)オブジェクトへの共有ポインタ。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Image](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)
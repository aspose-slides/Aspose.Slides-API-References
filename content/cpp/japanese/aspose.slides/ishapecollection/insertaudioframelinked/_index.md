---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API リファレンス
description: 外部オーディオファイルにリンクされた新しいオーディオフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。
type: docs
weight: 235
url: /ja/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) メソッド

外部オーディオファイルにリンクされた新しいオーディオフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | オーディオフレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しいオーディオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）。 |
| fname | [System::String](../../../system/string/) | リンクする外部オーディオファイルのパスまたは名前。 |

### 戻り値

新しく作成された[IAudioFrame](../../iaudioframe/)です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAudioFrame](../../iaudioframe/)
* クラス [String](../../../system/string/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
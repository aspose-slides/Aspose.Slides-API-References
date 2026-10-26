---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API リファレンス
description: 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。
type: docs
weight: 274
url: /ja/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) method

外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### 引数

| パラメータ | Type | 説明 |
| --- | --- | --- |
| index | **int32_t** | オーディオ フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しいオーディオ フレームの X 座標（ポイント単位）。 |
| y | **float** | 新しいオーディオ フレームの Y 座標（ポイント単位）。 |
| width | **float** | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| fname | [System::String](../../../system/string/) | リンクする外部オーディオ ファイルのパスまたは名前。 |

## 戻り値

新しく作成された[IAudioFrame](../../iaudioframe/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAudioFrame](../../iaudioframe/)
* クラス [String](../../../system/string/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
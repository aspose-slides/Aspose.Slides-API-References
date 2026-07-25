---
title: AddAudioFrameLinked()
second_title: Aspose.Slides for C++ API リファレンス
description: 外部オーディオファイルにリンクされた新しいオーディオフレームを作成し、シェイプコレクションの末尾に追加します。
type: docs
weight: 222
url: /ja/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) メソッド

外部オーディオファイルにリンクされた新しいオーディオフレームを作成し、シェイプコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいオーディオフレームのx座標（ポイント単位）。 |
| y | **float** | 新しいオーディオフレームのy座標（ポイント単位）。 |
| width | **float** | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいオーディオフレームの高さ（ポイント単位）。 |
| fname | [System::String](../../../system/string/) | リンクする外部オーディオファイルのパスまたは名前。 |

### 戻り値

新しく作成された[IAudioFrame](../../iaudioframe/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAudioFrame](../../iaudioframe/)
* クラス [String](../../../system/string/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
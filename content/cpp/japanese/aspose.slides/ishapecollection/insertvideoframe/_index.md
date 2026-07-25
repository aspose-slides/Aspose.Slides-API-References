---
title: InsertVideoFrame()
second_title: Aspose.Slides の C++ API リファレンス
description: 新しいビデオフレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。
type: docs
weight: 183
url: /ja/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) メソッド

新しいビデオフレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | ビデオフレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しいビデオフレームの x 座標（単位はポイント）。 |
| y | **float** | 新しいビデオフレームの y 座標（単位はポイント）。 |
| width | **float** | 新しいビデオフレームの幅（単位はポイント）。 |
| height | **float** | 新しいビデオフレームの高さ（単位はポイント）。 |
| fname | [System::String](../../../system/string/) | 埋め込むビデオ ファイルのパスまたは名前。 |

### 戻り値

新しく作成された [IVideoFrame](../../ivideoframe/)。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IVideoFrame](../../ivideoframe/)
* クラス [String](../../../system/string/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
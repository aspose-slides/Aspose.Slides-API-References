---
title: InsertVideoFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいビデオフレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。
type: docs
weight: 222
url: /ja/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) メソッド

新しいビデオフレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | ビデオフレームを挿入するゼロベースの index。 |
| x | **float** | 新しいビデオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいビデオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいビデオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいビデオフレームの高さ（ポイント単位）。 |
| fname | [System::String](../../../system/string/) | 埋め込むビデオ ファイルのパスまたは名前。 |

### 戻り値

新しく作成された [IVideoFrame](../../ivideoframe/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IVideoFrame](../../ivideoframe/)
* クラス [String](../../../system/string/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 170
url: /ja/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) メソッド

新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新しいビデオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいビデオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいビデオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいビデオフレームの高さ（ポイント単位）。 |
| fname | [System::String](../../../system/string/) | 埋め込むビデオ ファイルのパスまたは名前。 |

### 戻り値

新しく作成された [IVideoFrame](../../ivideoframe/)。

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) メソッド

新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新しいビデオフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しいビデオフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しいビデオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいビデオフレームの高さ（ポイント単位）。 |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | ビデオフレームに埋め込む [IVideo](../../ivideo/)。 |

### 戻り値

新しく作成された [IVideoFrame](../../ivideoframe/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IVideoFrame](../../ivideoframe/)
* クラス [String](../../../system/string/)
* クラス [IShapeCollection](../)
* クラス [IVideo](../../ivideo/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
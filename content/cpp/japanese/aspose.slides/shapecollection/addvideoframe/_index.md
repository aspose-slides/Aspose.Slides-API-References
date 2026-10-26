---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 209
url: /ja/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) メソッド


新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいビデオフレームの X 座標（ポイント単位）。 |
| y | **float** | 新しいビデオフレームの Y 座標（ポイント単位）。 |
| width | **float** | 新しいビデオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいビデオフレームの高さ（ポイント単位）。 |
| fname | [System::String](../../../system/string/) | 埋め込むビデオファイルのパスまたは名前。 |

### 戻り値

新しく作成された [IVideoFrame](../../ivideoframe/)。

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) メソッド


新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいビデオフレームの X 座標（ポイント単位）。 |
| y | **float** | 新しいビデオフレームの Y 座標（ポイント単位）。 |
| width | **float** | 新しいビデオフレームの幅（ポイント単位）。 |
| height | **float** | 新しいビデオフレームの高さ（ポイント単位）。 |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | ビデオフレームに埋め込む [IVideo](../../ivideo/)。 |

### 戻り値

新しく作成された [IVideoFrame](../../ivideoframe/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IVideoFrame](../../ivideoframe/)
* クラス [String](../../../system/string/)
* クラス [ShapeCollection](../)
* クラス [IVideo](../../ivideo/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
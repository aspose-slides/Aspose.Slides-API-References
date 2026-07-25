---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスに新しい Summary Zoom フレームを作成し、シェイプ コレクションに挿入します。
type: docs
weight: 157
url: /ja/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) メソッド

指定したインデックスに新しい Summary Zoom フレームを作成し、シェイプ コレクションに挿入します。

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | Summary Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい Summary Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Summary Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Summary Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Summary Zoom フレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 備考

このメソッドは、プレゼンテーション内のすべてのセクションのサマリー リンクを集約する Summary Zoom フレームを作成します。

この例は、コレクションの指定したインデックスに Summary Zoom オブジェクトを作成して挿入する方法を示します（\"Presentation.pptx\" プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）:

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISummaryZoomFrame](../../isummaryzoomframe/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
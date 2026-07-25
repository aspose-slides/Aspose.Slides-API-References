---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides の C++ API リファレンス
description: 新しい Summary Zoom フレームを作成し、指定したインデックスでシェイプ コレクションに挿入します。
type: docs
weight: 170
url: /ja/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) メソッド

新しい Summary Zoom フレームを作成し、指定したインデックスでシェイプ コレクションに挿入します。

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### 引数

| パラメーター | 型 | 説明 |
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

この例では、コレクションの指定インデックスに Summary Zoom オブジェクトを作成して挿入する方法を示します（"Presentation.pptx" プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
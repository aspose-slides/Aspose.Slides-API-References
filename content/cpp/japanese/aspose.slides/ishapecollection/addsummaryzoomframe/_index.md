---
title: AddSummaryZoomFrame()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 新しい Summary Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 144
url: /ja/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) method


新しい Summary Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい Summary Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Summary Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Summary Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Summary Zoom フレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 備考


このメソッドは、プレゼンテーション内のすべてのセクションのサマリー リンクを集約する Summary Zoom フレームを作成します。

この例は、コレクションの末尾に Summary Zoom オブジェクトを追加する方法を示しています（"Presentation.pptx" プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
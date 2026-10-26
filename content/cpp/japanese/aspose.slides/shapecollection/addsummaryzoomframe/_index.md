---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Summary Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 157
url: /ja/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) メソッド


新しい Summary Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新しい Summary Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Summary Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Summary Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Summary Zoom フレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [ISummaryZoomFrame](../../isummaryzoomframe/)。

## 備考


このメソッドは新しい Summary Zoom を作成し、このプレゼンテーションのすべてのセクションに対してオブジェクトのコレクションをその中に配置します。

この例は、コレクションの末尾に Summary Zoom オブジェクトを追加する方法を示します（\"Presentation.pptx\" プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）。
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISummaryZoomFrame](../../isummaryzoomframe/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
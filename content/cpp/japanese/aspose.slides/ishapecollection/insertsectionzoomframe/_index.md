---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Section Zoom フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。
type: docs
weight: 131
url: /ja/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) メソッド

指定されたインデックスで新しい [Section](../../section/) Zoom フレームを作成し、シェイプ コレクションに挿入します。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | [Section](../../section/) Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい [Section](../../section/) Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい [Section](../../section/) Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい [Section](../../section/) Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい [Section](../../section/) Zoom フレームの高さ（ポイント単位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom フレームが参照する [ISection](../../isection/)。このプレゼンテーションに属し、少なくとも 1 枚のスライドを含んでいる必要があります。 |

### 戻り値

新しく作成された [ISectionZoomFrame](../../isectionzoomframe/)。

## 備考

この例は、コレクションの指定されたインデックスに [Section](../../section/) Zoom オブジェクトを作成して挿入する方法を示しています（"Presentation.pptx" プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）:

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) メソッド

指定されたインデックスで、事前定義された画像を持つ新しい [Section](../../section/) Zoom フレームを作成し、シェイプ コレクションに挿入します。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | [Section](../../section/) Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい [Section](../../section/) Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい [Section](../../section/) Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい [Section](../../section/) Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい [Section](../../section/) Zoom フレームの高さ（ポイント単位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom フレームが参照する [ISection](../../isection/)。このプレゼンテーションに属し、少なくとも 1 枚のスライドを含んでいる必要があります。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom フレーム内に表示する画像。 |

### 戻り値

新しく作成された [ISectionZoomFrame](../../isectionzoomframe/)。

## 備考

この例は、コレクションの指定されたインデックスに [Section](../../section/) Zoom オブジェクトを作成して挿入する方法を示しています（"Presentation.pptx" プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）:

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISectionZoomFrame](../../isectionzoomframe/)
* クラス [ISection](../../isection/)
* クラス [IShapeCollection](../)
* クラス [IPPImage](../../ippimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
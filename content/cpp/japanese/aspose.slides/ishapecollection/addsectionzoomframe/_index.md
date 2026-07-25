---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ APIリファレンス
description: 新しいセクションズームフレームを作成し、シェイプコレクションの末尾に追加します。
type: docs
weight: 118
url: /ja/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) メソッド

新しい[Section](../../section/)ズームフレームを作成し、シェイプコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい[Section](../../section/)ズームフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい[Section](../../section/)ズームフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい[Section](../../section/)ズームフレームの幅（ポイント単位）。 |
| height | **float** | 新しい[Section](../../section/)ズームフレームの高さ（ポイント単位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/)ズームフレームが参照する [ISection](../../isection/)。このプレゼンテーションに属し、少なくとも1枚のスライドを含む必要があります。 |

## 戻り値

新しく作成された[ISectionZoomFrame](../../isectionzoomframe/)。

## 備考

この例は、コレクションの末尾に [Section](../../section/) ズームオブジェクトを追加する方法を示しています（"Presentation.pptx" プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）:
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) メソッド

事前定義された画像を持つ新しい[Section](../../section/)ズームフレームを作成し、シェイプコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい[Section](../../section/)ズームフレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい[Section](../../section/)ズームフレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい[Section](../../section/)ズームフレームの幅（ポイント単位）。 |
| height | **float** | 新しい[Section](../../section/)ズームフレームの高さ（ポイント単位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/)ズームフレームが参照する [ISection](../../isection/)。このプレゼンテーションに属し、少なくとも1枚のスライドを含む必要があります。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/)ズームフレーム内に表示する [IPPImage](../../ippimage/)。 |

## 戻り値

新しく作成された[ISectionZoomFrame](../../isectionzoomframe/)。

## 備考

この例は、コレクションの末尾に [Section](../../section/) ズームオブジェクトを追加する方法を示しています（"Presentation.pptx" プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）:
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISectionZoomFrame](../../isectionzoomframe/)
* クラス [ISection](../../isection/)
* クラス [IShapeCollection](../)
* クラス [IPPImage](../../ippimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
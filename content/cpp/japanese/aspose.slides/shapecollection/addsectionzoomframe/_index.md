---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 131
url: /ja/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) メソッド

新しい[Section](../../section/) Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい[Section](../../section/) Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい[Section](../../section/) Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい[Section](../../section/) Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい[Section](../../section/) Zoom フレームの高さ（ポイント単位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom フレームが参照する[ISection](../../isection/)；このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |

### 戻り値

新しく作成された[ISectionZoomFrame](../../isectionzoomframe/)。

## 備考

この例では、コレクションの末尾に[Section](../../section/) Zoom オブジェクトを追加する方法を示します（"Presentation.pptx" プレゼンテーションに少なくとも2つのセクションがあると仮定します）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) メソッド

事前に定義された画像を持つ新しい[Section](../../section/) Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい[Section](../../section/) Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい[Section](../../section/) Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい[Section](../../section/) Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい[Section](../../section/) Zoom フレームの高さ（ポイント単位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom フレームが参照する[ISection](../../isection/)；このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom フレーム内に表示する[IPPImage](../../ippimage/)。 |

### 戻り値

新しく作成された[ISectionZoomFrame](../../isectionzoomframe/)。

## 備考

この例では、コレクションの末尾に[Section](../../section/) Zoom オブジェクトを追加する方法を示します（"Presentation.pptx" プレゼンテーションに少なくとも2つのセクションがあると仮定します）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISectionZoomFrame](../../isectionzoomframe/)
* クラス [ISection](../../isection/)
* クラス [ShapeCollection](../)
* クラス [IPPImage](../../ippimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
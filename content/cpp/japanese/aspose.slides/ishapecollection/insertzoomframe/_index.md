---
title: InsertZoomFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Zoom フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。
type: docs
weight: 105
url: /ja/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) メソッド

新しい Zoom フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Zoom フレームの高さ（ポイント単位）。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom フレームが参照する [ISlide](../../islide/)。 |

### 戻り値

新しく作成された [IZoomFrame](../../izoomframe/)。

## 備考

この例は、コレクションの指定インデックスに Zoom オブジェクトを作成して挿入する方法を示しています（"Presentation.pptx" プレゼンテーションに少なくとも 2 枚のスライドがあると仮定します）:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) メソッド

事前に定義された画像を持つ新しい Zoom フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Zoom フレームを挿入するゼロベースのインデックス。 |
| x | **float** | 新しい Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Zoom フレームの高さ（ポイント単位）。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom フレームが参照する [ISlide](../../islide/)。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 参照されたスライド [IPPImage](../../ippimage/) の画像。 |

### 戻り値

新しく作成された [IZoomFrame](../../izoomframe/)。

## 備考

この例は、コレクションの指定インデックスに Zoom オブジェクトを作成して挿入する方法を示しています（"Presentation.pptx" プレゼンテーションに少なくとも 2 枚のスライドがあると仮定します）:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IZoomFrame](../../izoomframe/)
* クラス [ISlide](../../islide/)
* クラス [IShapeCollection](../)
* クラス [IPPImage](../../ippimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
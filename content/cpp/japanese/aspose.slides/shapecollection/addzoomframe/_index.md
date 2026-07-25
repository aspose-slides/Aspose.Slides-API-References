---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 105
url: /ja/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) メソッド


新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Zoom フレームの高さ（ポイント単位）。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom フレームが参照する [ISlide](../../islide/)。このプレゼンテーションに属している必要があります。 |

### 戻り値

新しく作成された [IZoomFrame](../../izoomframe/)。

## 備考


この例は、コレクションの末尾に Zoom オブジェクトを追加する方法を示しています（「Presentation.pptx」プレゼンテーションに少なくとも 2 枚のスライドがあると仮定します）: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) メソッド


新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しい Zoom フレームの x 座標（ポイント単位）。 |
| y | **float** | 新しい Zoom フレームの y 座標（ポイント単位）。 |
| width | **float** | 新しい Zoom フレームの幅（ポイント単位）。 |
| height | **float** | 新しい Zoom フレームの高さ（ポイント単位）。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom フレームが参照する [ISlide](../../islide/)。このプレゼンテーションに属している必要があります。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 参照スライド [IPPImage](../../ippimage/) 用の画像。 |

### 戻り値

新しく作成された [IZoomFrame](../../izoomframe/)。

## 備考


この例は、コレクションの末尾に Zoom オブジェクトを追加する方法を示しています（「Presentation.pptx」プレゼンテーションに少なくとも 2 枚のスライドがあると仮定します）: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## 参考

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IZoomFrame](../../izoomframe/)
* クラス [ISlide](../../islide/)
* クラス [ShapeCollection](../)
* クラス [IPPImage](../../ippimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
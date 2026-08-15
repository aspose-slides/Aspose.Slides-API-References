---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的 Zoom 框架，並將其添加到形狀集合的末端。
type: docs
weight: 92
url: /zh-hant/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) 方法

建立新的 Zoom 框架，並將其添加到形狀集合的末端。

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新 Zoom 框架的 x 座標，單位為點。 |
| y | **float** | 新 Zoom 框架的 y 座標，單位為點。 |
| width | **float** | 新 Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Zoom 框架的高度，單位為點。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框架所參照的 [ISlide](../../islide/)；必須屬於此簡報。 |

### 回傳值

新建立的 [IZoomFrame](../../izoomframe/)。

## 備註

此範例說明如何在集合的末端添加 Zoom 物件（假設 "Presentation.pptx" 簡報中至少有兩張投影片）：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) 方法

建立新的 Zoom 框架，並將其添加到形狀集合的末端。

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新 Zoom 框架的 x 座標，單位為點。 |
| y | **float** | 新 Zoom 框架的 y 座標，單位為點。 |
| width | **float** | 新 Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Zoom 框架的高度，單位為點。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框架所參照的 [ISlide](../../islide/)；必須屬於此簡報。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 所參照投影片 [IPPImage](../../ippimage/) 的影像。 |

### 回傳值

新建立的 [IZoomFrame](../../izoomframe/)。

## 備註

此範例說明如何在集合的末端添加 Zoom 物件（假設 "Presentation.pptx" 簡報中至少有兩張投影片）：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IZoomFrame](../../izoomframe/)
* 類別 [ISlide](../../islide/)
* 類別 [IShapeCollection](../)
* 類別 [IPPImage](../../ippimage/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
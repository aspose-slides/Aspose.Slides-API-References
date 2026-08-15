---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的 Zoom 框架，並將其加入至圖形集合的末端。
type: docs
weight: 105
url: /zh-hant/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) 方法


建立新的 Zoom 框架，並將其加入至圖形集合的末端。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新 Zoom 框架的 x 座標，以點為單位。 |
| y | **float** | 新 Zoom 框架的 y 座標，以點為單位。 |
| width | **float** | 新 Zoom 框架的寬度，以點為單位。 |
| height | **float** | 新 Zoom 框架的高度，以點為單位。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) 被 Zoom 框架參考；必須屬於此簡報。 |

### 傳回值

新建立的 [IZoomFrame](../../izoomframe/)。

## 備註


此範例示範將 Zoom 物件加入集合的末端（假設在 "Presentation.pptx" 簡報中至少有兩張投影片）：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) 方法


建立新的 Zoom 框架，並將其加入至圖形集合的末端。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新 Zoom 框架的 x 座標，以點為單位。 |
| y | **float** | 新 Zoom 框架的 y 座標，以點為單位。 |
| width | **float** | 新 Zoom 框架的寬度，以點為單位。 |
| height | **float** | 新 Zoom 框架的高度，以點為單位。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) 被 Zoom 框架參考；必須屬於此簡報。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 參考投影片 [IPPImage](../../ippimage/) 的影像。 |

### 傳回值

新建立的 [IZoomFrame](../../izoomframe/)。

## 備註


此範例示範將 Zoom 物件加入集合的末端（假設在 "Presentation.pptx" 簡報中至少有兩張投影片）：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IZoomFrame](../../izoomframe/)
* 類別 [ISlide](../../islide/)
* 類別 [ShapeCollection](../)
* 類別 [IPPImage](../../ippimage/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
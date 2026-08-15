---
title: InsertZoomFrame()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定的索引處建立新的 Zoom 框架，並將其插入形狀集合。
type: docs
weight: 118
url: /zh-hant/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) 方法


建立一個新的 Zoom 框架，並將其插入到指定索引的形狀集合中。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入 Zoom 框架的零基索引。 |
| x | **float** | 新 Zoom 框架的 x 座標（單位為點）。 |
| y | **float** | 新 Zoom 框架的 y 座標（單位為點）。 |
| width | **float** | 新 Zoom 框架的寬度（單位為點）。 |
| height | **float** | 新 Zoom 框架的高度（單位為點）。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框架所參考的 [ISlide](../../islide/)。 |

### 回傳值

新建立的 [IZoomFrame](../../izoomframe/)。

## 備註


此範例示範在集合的指定索引處建立並插入 Zoom 物件（假設在 "Presentation.pptx" 簡報中至少有兩張投影片）：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) 方法


建立一個帶有預先定義圖像的新 Zoom 框架，並將其插入到指定索引的形狀集合中。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入 Zoom 框架的零基索引。 |
| x | **float** | 新 Zoom 框架的 x 座標（單位為點）。 |
| y | **float** | 新 Zoom 框架的 y 座標（單位為點）。 |
| width | **float** | 新 Zoom 框架的寬度（單位為點）。 |
| height | **float** | 新 Zoom 框架的高度（單位為點）。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框架所參考的 [ISlide](../../islide/)。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 參考投影片 [IPPImage](../../ippimage/) 的圖像。 |

### 回傳值

新建立的 [IZoomFrame](../../izoomframe/)。

## 備註


此範例示範在集合的指定索引處建立並插入 Zoom 物件（假設在 "Presentation.pptx" 簡報中至少有兩張投影片）：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IZoomFrame](../../izoomframe/)
* 類別 [ISlide](../../islide/)
* 類別 [ShapeCollection](../)
* 類別 [IPPImage](../../ippimage/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
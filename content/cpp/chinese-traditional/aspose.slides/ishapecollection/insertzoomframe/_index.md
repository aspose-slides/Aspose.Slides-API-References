---
title: InsertZoomFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的 Zoom 框架，並將其插入至指定索引的圖形集合中。
type: docs
weight: 105
url: /zh-hant/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method

建立新的 Zoom 框架，並將其插入至指定索引的圖形集合中。

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 插入 Zoom 框架的零基索引。 |
| x | **float** | 新 Zoom 框架的 x 座標，單位為點。 |
| y | **float** | 新 Zoom 框架的 y 座標，單位為點。 |
| width | **float** | 新 Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Zoom 框架的高度，單位為點。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框架參照的 [ISlide](../../islide/)。 |

### 回傳值

The newly created [IZoomFrame](../../izoomframe/).

## 備註

此範例示範在集合的指定索引處建立並插入 Zoom 物件（假設 "Presentation.pptx" 簡報中至少有兩張投影片）：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

建立具有預先定義影像的新 Zoom 框架，並將其插入至指定索引的圖形集合中。

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 插入 Zoom 框架的零基索引。 |
| x | **float** | 新 Zoom 框架的 x 座標，單位為點。 |
| y | **float** | 新 Zoom 框架的 y 座標，單位為點。 |
| width | **float** | 新 Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Zoom 框架的高度，單位為點。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框架參照的 [ISlide](../../islide/)。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 參照投影片 [IPPImage](../../ippimage/) 的圖像。 |

### 回傳值

The newly created [IZoomFrame](../../izoomframe/).

## 備註

此範例示範在集合的指定索引處建立並插入 Zoom 物件（假設 "Presentation.pptx" 簡報中至少有兩張投影片）：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
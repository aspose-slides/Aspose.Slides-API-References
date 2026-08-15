---
title: set_TileOffsetY()
second_title: Aspose.Slides C++ API 參考
description: 設定紋理相對於形狀原點的垂直偏移量（以點為單位）。正值會將紋理向下移動，負值則會向上移動。寫入 float。
type: docs
weight: 313
url: /zh-hant/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) 方法

設定紋理相對於形狀原點的垂直偏移量（以點為單位）。正值會將紋理向下移動，負值則會向上移動。寫入 **float**。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the vertical offset of the texture to -50 points
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 另見

* 類別 [PictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
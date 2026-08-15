---
title: get_TileOffsetX()
second_title: Aspose.Slides for C++ API 參考
description: 返回紋理相對於形狀原點的水平偏移量（以點為單位）。正值會將紋理向右移動，負值會將其向左移動。讀取 float.
type: docs
weight: 274
url: /zh-hant/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() 方法

返回紋理相對於形狀原點的水平偏移量（以點為單位）。正值會將紋理向右移動，負值則會將其向左移動。Read **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 獲取形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 設定紋理的水平偏移量為 20 點
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 參見

* 類別 [PictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
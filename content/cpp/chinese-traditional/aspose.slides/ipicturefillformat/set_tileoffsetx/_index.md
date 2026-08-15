---
title: set_TileOffsetX()
second_title: Aspose.Slides C++ API 參考
description: 設定紋理相對於形狀原點的水平偏移量（以點為單位）。正值會將紋理向右移動，負值會向左移動。寫入 float.
type: docs
weight: 287
url: /zh-hant/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) 方法


設定紋理相對於形狀原點的水平偏移量（以點為單位）。正值會將紋理向右移動，負值則會向左移動。寫入 **float**。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 設定紋理的水平偏移量為 20 點
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 另見

* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
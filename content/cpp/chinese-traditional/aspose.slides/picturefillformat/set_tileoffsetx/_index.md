---
title: set_TileOffsetX()
second_title: Aspose.Slides for C++ API 參考
description: 設定紋理相對於形狀原點的水平偏移量（單位為點）。正值會將紋理向右移動，負值則會向左移動。寫入 float.
type: docs
weight: 287
url: /zh-hant/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) 方法

設定紋理相對於形狀原點的水平偏移量（單位為點）。正值會將紋理向右移動，負值則會向左移動。寫入 **float**。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 將圖片填充模式設為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理的水平偏移設定為 20 點
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 另見

* 類別 [PictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
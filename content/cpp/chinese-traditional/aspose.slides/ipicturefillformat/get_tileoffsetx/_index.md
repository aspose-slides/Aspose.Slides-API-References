---
title: get_TileOffsetX()
second_title: Aspose.Slides C++ API 參考
description: 返回紋理相對於形狀原點的水平偏移量，單位為點。正值會使紋理向右移動，負值會使其向左移動。Read float.
type: docs
weight: 274
url: /zh-hant/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() 方法

返回紋理相對於形狀原點的水平偏移量，單位為點。正值會使紋理向右移動，負值會使其向左移動。Read **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## 備註

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 將圖片填充模式設定為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理的水平偏移量設定為 20 點
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 另見

* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)
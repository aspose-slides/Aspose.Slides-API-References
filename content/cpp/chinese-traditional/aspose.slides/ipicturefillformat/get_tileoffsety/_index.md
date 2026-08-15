---
title: get_TileOffsetY()
second_title: Aspose.Slides for C++ API 參考
description: 返回紋理相對於形狀原點的垂直偏移（單位為點）。正值會將紋理向下移動，負值則會向上移動。讀取 float.
type: docs
weight: 300
url: /zh-hant/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() 方法

返回紋理相對於形狀原點的垂直偏移（單位為點）。正值會將紋理向下移動，負值則會向上移動。讀取 **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## 備註

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 設定紋理的垂直偏移為 -50 點
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 另見

* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)
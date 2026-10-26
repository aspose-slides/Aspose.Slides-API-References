---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定紋理相對於圖形原點的垂直位移（以點為單位）。正值會使紋理向下移動，負值則會使其向上移動。寫入 float.
type: docs
weight: 313
url: /zh-hant/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) 方法

設定紋理相對於圖形原點的垂直位移（以點為單位）。正值會使紋理向下移動，負值則會使其向上移動。寫入 **float**。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 將圖片填充模式設定為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理的垂直位移設定為 -50 點
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 另見

* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
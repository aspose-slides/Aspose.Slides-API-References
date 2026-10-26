---
title: get_TileScaleX()
second_title: Aspose.Slides for C++ API 參考
description: 以百分比返回紋理填充的水平比例。讀取 float.
type: docs
weight: 326
url: /zh-hant/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() 方法


返回紋理填充的水平比例（以百分比表示）。讀取 **float**。

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 設定紋理的水平比例為 120 百分比
pictureFillFormat->set_TileScaleX(120.0f);
```

## 另請參閱

* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
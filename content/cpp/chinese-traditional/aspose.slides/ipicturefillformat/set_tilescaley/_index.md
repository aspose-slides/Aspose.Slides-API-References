---
title: set_TileScaleY()
second_title: Aspose.Slides for C++ API 參考
description: 設定紋理填充的垂直比例為百分比。寫入 float.
type: docs
weight: 365
url: /zh-hant/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) 方法


設定紋理填充的垂直比例為百分比。寫入 **float**。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理的垂直比例設定為 120 百分比
pictureFillFormat->set_TileScaleY(120.0f);
```

## 另請參閱

* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
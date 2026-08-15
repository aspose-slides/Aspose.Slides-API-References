---
title: set_TileScaleX()
second_title: Aspose.Slides for C++ API 參考
description: 將紋理填充的水平比例設為百分比。寫入 float.
type: docs
weight: 339
url: /zh-hant/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) 方法


將紋理填充的水平比例設為百分比。寫入 **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 將圖片填充模式設定為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理的水平比例設定為 120 百分比
pictureFillFormat->set_TileScaleX(120.0f);
```

## 參見

* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
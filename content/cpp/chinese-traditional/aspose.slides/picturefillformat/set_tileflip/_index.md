---
title: set_TileFlip()
second_title: Aspose.Slides for C++ API 參考
description: "將紋理圖塊繞其水平、垂直或兩個軸翻轉。寫入 Slides::TileFlip."
type: docs
weight: 417
url: /zh-hant/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) 方法


將紋理圖塊繞其水平、垂直或兩個軸翻轉。寫入 [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## 備註


預設為 [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 獲取形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理圖塊繞其垂直軸翻轉。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## 另見

* Enum [TileFlip](../../tileflip/)
* 類別 [PictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: get_TileFlip()
second_title: Aspose.Slides C++ API 參考
description: "將紋理圖塊繞其水平、垂直或兩個軸翻轉。請參閱 Slides::TileFlip."
type: docs
weight: 404
url: /zh-hant/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() 方法


將紋理圖塊繞其水平、垂直或兩個軸翻轉。請參閱 [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## 備註


預設為 [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得圖形的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 將圖片填充模式設為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理圖塊繞其垂直軸翻轉。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## 另請參閱

* Enum [TileFlip](../../tileflip/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
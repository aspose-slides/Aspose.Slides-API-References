---
title: set_TileFlip()
second_title: Aspose.Slides for C++ API 參考文件
description: "將紋理圖塊繞其水平、垂直或兩個軸翻轉。寫入 Slides::TileFlip."
type: docs
weight: 417
url: /zh-hant/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) 方法

將紋理圖塊繞其水平、垂直或兩個軸翻轉。寫入 [Slides::TileFlip](../../tileflip/)。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## 備註

預設為 [TileFlip::NoFlip](../../tileflip/)。 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 將圖片填充模式設定為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理圖塊繞其垂直軸翻轉。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## 另見

* 列舉 [TileFlip](../../tileflip/)
* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)
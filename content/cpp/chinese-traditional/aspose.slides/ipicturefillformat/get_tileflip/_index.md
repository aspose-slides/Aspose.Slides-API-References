---
title: get_TileFlip()
second_title: Aspose.Slides for C++ API 參考
description: "水平、垂直或兩個軸上翻轉紋理圖塊。請參閱 Slides::TileFlip。"
type: docs
weight: 404
url: /zh-hant/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() 方法

在水平、垂直或兩個軸上翻轉紋理圖塊。請參閱 [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## 備註

預設為 [TileFlip::NoFlip](../../tileflip/)。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 在垂直軸上翻轉紋理圖塊。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## 另見

* Enum [TileFlip](../../tileflip/)
* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
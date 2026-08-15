---
title: get_TileAlignment()
second_title: Aspose.Slides for C++ API 參考
description: 返回紋理在形狀內的對齊方式。此設定控制紋理圖樣的起始點以及它在形狀上的重複方式。請參閱 RectangleAlignment。
type: docs
weight: 378
url: /zh-hant/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() 方法

返回紋理在形狀內的對齊方式。此設定控制紋理圖樣的起始點以及它在形狀上的重複方式。閱讀 [RectangleAlignment](../../rectanglealignment/)。

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## 備註

預設為 [RectangleAlignment::TopLeft](../../rectanglealignment/)。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 將圖片填充模式設為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 設定平鋪的對齊方式為右下角
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 另請參閱

* 列舉 [RectangleAlignment](../../rectanglealignment/)
* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
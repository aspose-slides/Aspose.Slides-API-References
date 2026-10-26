---
title: set_TileAlignment()
second_title: Aspose.Slides C++ API 參考
description: 設定紋理在形狀內的對齊方式。此設定控制紋理圖案的起始點以及它在形狀中的重複方式。寫入 RectangleAlignment.
type: docs
weight: 391
url: /zh-hant/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) 方法

設定紋理在形狀內的對齊方式。此設定控制紋理圖案的起始點以及它在形狀中的重複方式。寫入 [RectangleAlignment](../../rectanglealignment/)。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## 備註

預設為 [RectangleAlignment::TopLeft](../../rectanglealignment/)。  


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 設定平鋪的對齊方式為右下角
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 另見

* 列舉 [RectangleAlignment](../../rectanglealignment/)
* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
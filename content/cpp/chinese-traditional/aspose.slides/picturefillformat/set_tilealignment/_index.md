---
title: set_TileAlignment()
second_title: Aspose.Slides C++ API 參考
description: 設定紋理在形狀內的對齊方式。此設定控制紋理圖案的起始點以及它在形狀上的重複方式。寫入 RectangleAlignment.
type: docs
weight: 391
url: /zh-hant/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) 方法


設定紋理在形狀內的對齊方式。此設定控制紋理圖案的起始點以及它在形狀上的重複方式。寫入 [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## 備註


預設為 [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將平鋪的對齊方式設定為右下角
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 另請參閱

* Enum [RectangleAlignment](../../rectanglealignment/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
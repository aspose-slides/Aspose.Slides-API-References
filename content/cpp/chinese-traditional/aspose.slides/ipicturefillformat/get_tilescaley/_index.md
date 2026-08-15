---
title: get_TileScaleY()
second_title: Aspose.Slides for C++ API 參考
description: 返回紋理填充的垂直比例，作為百分比。讀取 float.
type: docs
weight: 352
url: /zh-hant/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() 方法

返回紋理填充的垂直比例，作為百分比。讀取 **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## 備註

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 設定紋理的垂直比例為 120 百分比
pictureFillFormat->set_TileScaleY(120.0f);
```

## 另見

* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
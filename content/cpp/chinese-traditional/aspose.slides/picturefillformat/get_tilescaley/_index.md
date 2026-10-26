---
title: get_TileScaleY()
second_title: Aspose.Slides for C++ API 參考文件
description: 以百分比返回紋理填充的垂直比例。讀取 float。
type: docs
weight: 352
url: /zh-hant/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() 方法

返回紋理填充的垂直比例，以百分比表示。讀取 **float**。

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## 備註

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 將圖片填充模式設為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理的垂直比例設定為 120 百分比
pictureFillFormat->set_TileScaleY(120.0f);
```

## 另見

* 類別 [PictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
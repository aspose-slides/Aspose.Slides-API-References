---
title: get_TileOffsetY()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回紋理相對於形狀原點的垂直位移（單位為點）。正值會使紋理向下移動，負值會使其向上移動。讀取 float.
type: docs
weight: 300
url: /zh-hant/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() 方法

返回紋理相對於形狀原點的垂直位移（單位為點）。正值會讓紋理向下移動，負值會讓其向上移動。讀取 **float**。

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## 備註


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為平鋪
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 設定紋理的垂直位移為 -50 點
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 參見

* 類別 [PictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
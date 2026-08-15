---
title: set_TileScaleX()
second_title: Aspose.Slides C++ API 參考文件
description: 設定紋理填充的水平比例，以百分比表示。寫入 float.
type: docs
weight: 339
url: /zh-hant/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) 方法


設定紋理填充的水平比例，以百分比表示。寫入 **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得形狀的圖片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 設定圖片填充模式為 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 將紋理的水平比例設定為 120%
pictureFillFormat->set_TileScaleX(120.0f);
```

## 另請參閱

* 類別 [PictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
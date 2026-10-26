---
title: get_TileScaleX()
second_title: Aspose.Slides for C++ API 参考
description: 返回纹理填充的水平比例，以百分比表示。读取 float.
type: docs
weight: 326
url: /zh/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() 方法

返回纹理填充的水平比例，以百分比表示。读取 **float**。

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## 备注


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 设置图片填充模式为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的水平比例设置为 120 百分比
pictureFillFormat->set_TileScaleX(120.0f);
```

## 另请参阅

* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
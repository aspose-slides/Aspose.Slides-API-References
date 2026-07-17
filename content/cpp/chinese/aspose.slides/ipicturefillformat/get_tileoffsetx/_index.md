---
title: get_TileOffsetX()
second_title: Aspose.Slides for C++ API 参考
description: 返回纹理相对于形状原点的水平偏移，以点为单位。正值将纹理向右移动，负值将其向左移动。读取 float.
type: docs
weight: 274
url: /zh/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() method

返回纹理相对于形状原点的水平偏移，以点为单位。正值将纹理向右移动，负值将其向左移动。读取 **float**。

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## 备注

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的水平偏移设置为 20 点
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 另请参见

* 类 [IPictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
---
title: get_TileOffsetX()
second_title: Aspose.Slides for C++ API 参考
description: 返回纹理相对于形状原点的水平偏移量，单位为点。正值将纹理向右移动，负值将纹理向左移动。读取 float。
type: docs
weight: 274
url: /zh/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() 方法

返回纹理相对于形状原点的水平偏移量，单位为点。正值将纹理向右移动，负值将纹理向左移动。读取 **float**。

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## 备注


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 设置图片填充模式为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 设置纹理的水平偏移量为 20 点
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 另请参见

* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
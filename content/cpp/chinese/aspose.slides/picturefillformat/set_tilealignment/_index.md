---
title: set_TileAlignment()
second_title: Aspose.Slides C++ API 参考
description: 设置纹理在形状内的对齐方式。此设置控制纹理图案的起始点以及它在形状上的重复方式。写入 RectangleAlignment。
type: docs
weight: 391
url: /zh/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) 方法

设置纹理在形状内的对齐方式。此设置控制纹理图案的起始点以及它在形状上的重复方式。写入 [RectangleAlignment](../../rectanglealignment/)。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## 备注

默认是 [RectangleAlignment::TopLeft](../../rectanglealignment/)。 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为平铺
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将平铺的对齐方式设置为右下角
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 另见

* 枚举 [RectangleAlignment](../../rectanglealignment/)
* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
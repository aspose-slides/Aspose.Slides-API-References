---
title: get_TileAlignment()
second_title: Aspose.Slides C++ API 参考
description: 返回纹理在形状内的对齐方式。此设置控制纹理图案的起始点以及它在形状中的重复方式。阅读 RectangleAlignment.
type: docs
weight: 378
url: /zh/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() 方法


返回纹理在形状内的对齐方式。此设置控制纹理图案的起始点以及它在形状中的重复方式。阅读 [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## 备注


默认是 [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将平铺的对齐方式设置为右下
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 另请参见

* Enum [RectangleAlignment](../../rectanglealignment/)
* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
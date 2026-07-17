---
title: set_TileFlip()
second_title: Aspose.Slides for C++ API 参考
description: "水平、垂直或两个轴翻转纹理平铺。写入 Slides::TileFlip。"
type: docs
weight: 417
url: /zh/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) 方法

水平、垂直或两个轴翻转纹理平铺。写入 [Slides::TileFlip](../../tileflip/)。

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## 备注

默认是 [TileFlip::NoFlip](../../tileflip/)。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 在垂直轴上翻转纹理平铺。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## 另请参阅

* 枚举 [TileFlip](../../tileflip/)
* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
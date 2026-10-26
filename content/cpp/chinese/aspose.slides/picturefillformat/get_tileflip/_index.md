---
title: get_TileFlip()
second_title: Aspose.Slides C++ API 参考
description: "在水平、垂直或两个轴上翻转纹理瓦片。阅读 Slides::TileFlip."
type: docs
weight: 404
url: /zh/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() 方法


在水平、垂直或两个轴上翻转纹理瓦片。阅读 [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## 备注


默认是 [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为平铺
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 沿垂直轴翻转纹理平铺。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## 另见

* 枚举 [TileFlip](../../tileflip/)
* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
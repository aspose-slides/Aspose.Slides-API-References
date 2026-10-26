---
title: get_TileFlip()
second_title: Aspose.Slides for C++ API 参考
description: "将纹理平铺沿水平、垂直或两轴翻转。阅读 Slides::TileFlip。"
type: docs
weight: 404
url: /zh/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() 方法

将纹理平铺沿水平、垂直或两个轴翻转。阅读 [Slides::TileFlip](../../tileflip/)。

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## 备注

默认是 [TileFlip::NoFlip](../../tileflip/)。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为平铺
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 沿垂直轴翻转纹理平铺。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## 另请参见

* 枚举 [TileFlip](../../tileflip/)
* 类 [IPictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
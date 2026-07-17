---
title: set_TileFlip()
second_title: Aspose.Slides C++ API 参考
description: "将纹理瓦片围绕其水平、垂直或两个轴翻转。写入 Slides::TileFlip。"
type: docs
weight: 417
url: /zh/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) 方法


将纹理瓦片围绕其水平、垂直或两个轴翻转。写入 [Slides::TileFlip](../../tileflip/)。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
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

// 将纹理瓦片围绕其垂直轴翻转。
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## 另见

* 枚举 [TileFlip](../../tileflip/)
* 类 [IPictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
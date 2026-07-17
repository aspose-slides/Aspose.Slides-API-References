---
title: get_TileScaleX()
second_title: Aspose.Slides C++ API 参考
description: 返回纹理填充的水平比例，单位为百分比。读取 float.
type: docs
weight: 326
url: /zh/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() 方法

返回纹理填充的水平比例，单位为百分比。读取 **float**。

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的水平比例设置为 120%
pictureFillFormat->set_TileScaleX(120.0f);
```

## 另请参阅

* 类 [IPictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
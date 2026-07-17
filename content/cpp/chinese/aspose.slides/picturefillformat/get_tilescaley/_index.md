---
title: get_TileScaleY()
second_title: Aspose.Slides for C++ API 参考
description: 返回纹理填充的垂直比例，单位为百分比。读取 float.
type: docs
weight: 352
url: /zh/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() 方法


返回纹理填充的垂直比例，单位为百分比。读取 **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的垂直比例设置为 120%
pictureFillFormat->set_TileScaleY(120.0f);
```

## 另见

* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
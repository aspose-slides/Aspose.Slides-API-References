---
title: get_TileScaleY()
second_title: Aspose.Slides C++ API 参考
description: 返回纹理填充的垂直比例，以百分比表示。读取 float.
type: docs
weight: 352
url: /zh/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() 方法


返回纹理填充的垂直比例，以百分比表示。读取 **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## 备注


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的垂直比例设置为 120 百分比
pictureFillFormat->set_TileScaleY(120.0f);
```

## 另见

* 类 [IPictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
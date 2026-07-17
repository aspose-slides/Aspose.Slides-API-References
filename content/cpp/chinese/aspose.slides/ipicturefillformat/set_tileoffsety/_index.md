---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API 参考
description: 设置纹理相对于形状原点的垂直偏移（单位为点）。正值会将纹理向下移动，负值会将纹理向上移动。写入 float.
type: docs
weight: 313
url: /zh/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) 方法

设置纹理相对于形状原点的垂直偏移（单位为点）。正值会将纹理向下移动，负值会将纹理向上移动。写入 **float**。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为平铺
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的垂直偏移设置为 -50 点
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 另见

* 类 [IPictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
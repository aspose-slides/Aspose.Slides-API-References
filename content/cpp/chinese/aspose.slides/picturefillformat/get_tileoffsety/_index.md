---
title: get_TileOffsetY()
second_title: Aspose.Slides C++ API 参考
description: 返回纹理相对于形状原点的垂直偏移量，单位为点。正值会使纹理向下移动，负值会使其向上移动。读取 float。
type: docs
weight: 300
url: /zh/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() 方法


返回纹理相对于形状原点的垂直偏移量，单位为点。正值使纹理向下移动，负值使其向上移动。读取 **float**。

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的垂直偏移设置为 -50 点
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 另请参阅

* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
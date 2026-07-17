---
title: set_TileOffsetX()
second_title: Aspose.Slides C++ API 参考
description: 设置纹理相对于形状原点的水平偏移量，单位为点。正值将纹理向右移动，负值将纹理向左移动。写入 float。
type: docs
weight: 287
url: /zh/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) 方法


设置纹理相对于形状原点的水平偏移量，单位为点。正值将纹理向右移动，负值将纹理向左移动。写入 **float**。

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为 Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的水平偏移设置为 20 点
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 另请参见

* 类 [IPictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
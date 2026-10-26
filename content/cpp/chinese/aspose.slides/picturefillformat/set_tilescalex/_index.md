---
title: set_TileScaleX()
second_title: Aspose.Slides C++ API 参考
description: 将纹理填充的水平比例设置为百分比。写入 float.
type: docs
weight: 339
url: /zh/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) 方法


将纹理填充的水平比例设置为百分比。写入 **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## 备注



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取形状的图片填充格式
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 将图片填充模式设置为平铺
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 将纹理的水平比例设置为 120%
pictureFillFormat->set_TileScaleX(120.0f);
```

## 另见

* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
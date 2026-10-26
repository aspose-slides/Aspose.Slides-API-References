---
title: get_ImageType()
second_title: Aspose.Slides C++ API 参考
description: "获取 Zoom 对象的图像类型。阅读 ZoomImageType。默认值：Preview"
type: docs
weight: 1
url: /zh/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() 方法

获取 Zoom 对象的图像类型。阅读 [ZoomImageType](../../zoomimagetype/)。默认值：Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## 备注

指定 Zoom 对象是使用幻灯片预览还是封面图像。

下面示例演示将 Image Type 更改为 Preview 值。在此情况下，Zoom 对象的当前图像会更改为幻灯片图像：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## 另见

* 枚举 [ZoomImageType](../../zoomimagetype/)
* 类 [ZoomObject](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
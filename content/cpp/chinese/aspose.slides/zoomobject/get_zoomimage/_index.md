---
title: get_ZoomImage()
second_title: Aspose.Slides for C++ API 参考
description: 获取缩放对象的图像。阅读 IPPImage。
type: docs
weight: 79
url: /zh/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() 方法

获取缩放对象的图像。阅读 [IPPImage](../../ippimage/)。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## 备注

示例演示了更改 Zoom 对象的图像：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPPImage](../../ippimage/)
* 类 [ZoomObject](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
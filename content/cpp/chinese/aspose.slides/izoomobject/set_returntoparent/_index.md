---
title: set_ReturnToParent()
second_title: Aspose.Slides for C++ API 参考
description: "设置幻灯片中的导航行为。写入 bool。默认值：false"
type: docs
weight: 40
url: /zh/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) method


设置幻灯片中的导航行为。写入 **bool**。默认值：false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## 备注


属性的 true 值指定在幻灯片中的返回父级导航行为。 

示例： 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 另见

* 类 [IZoomObject](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
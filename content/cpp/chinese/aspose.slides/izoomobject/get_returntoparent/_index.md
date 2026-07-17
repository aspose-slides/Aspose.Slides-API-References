---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API 参考
description: "获取幻灯片放映中的导航行为。读取 bool。默认值：false"
type: docs
weight: 27
url: /zh/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() 方法


获取幻灯片放映中的导航行为。读取 **bool**。默认值：false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## 备注


属性的真实值指定在幻灯片放映中返回父级的导航行为。 

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
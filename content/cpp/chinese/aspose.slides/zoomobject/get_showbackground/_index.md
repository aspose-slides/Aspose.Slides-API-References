---
title: get_ShowBackground()
second_title: Aspose.Slides C++ API 参考
description: "获取指定 Zoom 是否使用目标幻灯片背景的值。读取 bool。默认值：true"
type: docs
weight: 53
url: /zh/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() 方法


获取指定 Zoom 是否使用目标幻灯片背景的值。读取 **bool**。默认值：true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## 备注


示例演示了移除 Zoom 对象的图像背景： 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## 另见

* 类 [ZoomObject](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
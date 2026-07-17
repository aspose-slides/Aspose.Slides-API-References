---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API 参考
description: "设置指定 Zoom 是否使用目标幻灯片背景的值。写入 bool。默认值：true"
type: docs
weight: 66
url: /zh/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) 方法


设置指定 Zoom 是否使用目标幻灯片背景的值。写入 **bool**。默认值：true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## 备注


示例演示了如何移除 Zoom 对象的图像背景：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## 参见

* 类 [ZoomObject](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API 参考
description: "获取幻灯片放映中的导航行为。读取 bool。默认值：false"
type: docs
weight: 27
url: /zh/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() 方法

获取幻灯片放映中的导航行为。读取 **bool**。默认值：false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## 备注

属性的 True 值指定幻灯片放映中的返回父级导航行为。

示例：
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 另见

* 类 [ZoomObject](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
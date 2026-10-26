---
title: set_ReturnToParent()
second_title: Aspose.Slides C++ API 参考
description: "设置幻灯片放映中的导航行为。写入 bool。默认值：false"
type: docs
weight: 40
url: /zh/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) 方法

设置幻灯片放映中的导航行为。写入 **bool**。默认值：false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## 备注

属性为 true 时指定在幻灯片放映中返回父级的导航行为。

示例：
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 另见

* 类 [ZoomObject](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
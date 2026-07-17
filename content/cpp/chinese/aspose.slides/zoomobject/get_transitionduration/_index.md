---
title: get_TransitionDuration()
second_title: Aspose.Slides C++ API 参考
description: "获取 Zoom 与幻灯片之间过渡的持续时间。读取 float。默认值：1.0f"
type: docs
weight: 105
url: /zh/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() 方法

获取 Zoom 与幻灯片之间过渡的持续时间。读取 **float**。默认值：1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## 备注

如果未指定 (TransitionDur = 0)，将使用目标幻灯片的过渡以及与该过渡关联的时间设置。

下面的示例演示了如何更改 Zoom 与幻灯片之间过渡的持续时间：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## 另请参见

* 类 [ZoomObject](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
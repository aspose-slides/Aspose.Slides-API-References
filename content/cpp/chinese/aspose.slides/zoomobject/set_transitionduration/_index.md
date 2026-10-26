---
title: set_TransitionDuration()
second_title: Aspose.Slides C++ API 参考
description: "设置 Zoom 与幻灯片之间过渡的持续时间。写入 float。默认值：1.0f"
type: docs
weight: 118
url: /zh/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) 方法

设置 Zoom 与幻灯片之间过渡的持续时间。写入 **float**。默认值：1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## 备注

如果未指定 (TransitionDur = 0)，它将使用目标幻灯片的过渡以及与该过渡关联的时间。

以下示例演示了更改 Zoom 与幻灯片之间过渡的持续时间：
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
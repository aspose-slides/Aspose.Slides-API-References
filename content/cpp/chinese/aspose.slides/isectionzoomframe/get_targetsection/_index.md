---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API 参考
description: 获取与 Section Zoom 对象关联的节对象。阅读 ISection.
type: docs
weight: 1
url: /zh/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() 方法


获取与 [Section](../../section/) Zoom 对象关联的节对象。阅读 [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## 备注


此示例演示更改目标节并为节缩放对象创建新图像：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISection](../../isection/)
* 类 [ISectionZoomFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
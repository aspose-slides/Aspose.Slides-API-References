---
title: set_TargetSection()
second_title: Aspose.Slides C++ API 参考
description: 设置 Section Zoom 对象链接的节对象。写入 ISection。
type: docs
weight: 14
url: /zh/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) method

设置该 [Section](../../section/) Zoom 对象链接的节对象。写入 [ISection](../../isection/)。

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## 备注

此示例演示更改目标节并为节缩放对象创建新图像：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISection](../../isection/)
* 类 [ISectionZoomFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
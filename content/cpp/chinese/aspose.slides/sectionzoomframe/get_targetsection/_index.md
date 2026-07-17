---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API 参考
description: 获取 Section Zoom 对象链接到的章节对象。阅读 ISection.
type: docs
weight: 1
url: /zh/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() 方法

获取 [Section](../../section/) Zoom 对象链接到的章节对象。阅读 [ISection](../../isection/)。

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## 备注

下面的示例演示了更改目标章节并为章节缩放对象创建新图像：
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISection](../../isection/)
* 类 [SectionZoomFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API 参考
description: 设置 Section Zoom 对象链接的章节对象。写入 ISection.
type: docs
weight: 14
url: /zh/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) 方法

设置 [Section](../../section/) Zoom 对象链接的章节对象。写入 [ISection](../../isection/)。

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## 备注

以下示例演示了更改目标章节并为章节缩放对象创建新图像：
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
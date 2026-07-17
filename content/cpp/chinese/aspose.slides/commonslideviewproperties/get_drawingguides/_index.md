---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ API 参考
description: 返回绘图参考线的集合。只读 IDrawingGuidesCollection
type: docs
weight: 53
url: /zh/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() 方法


返回绘图参考线的集合。只读 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## 备注


以下示例代码展示了如何在 PowerPoint 演示文稿中添加新的绘图参考线。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// 在幻灯片中心右侧添加新的垂直绘图参考线
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// 在幻灯片中心下方添加新的水平绘图参考线
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 类 [CommonSlideViewProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
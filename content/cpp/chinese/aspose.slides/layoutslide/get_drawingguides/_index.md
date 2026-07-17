---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ API 参考
description: 返回布局幻灯片的绘图参考线集合。只读 IDrawingGuidesCollection
type: docs
weight: 118
url: /zh/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() 方法


返回布局幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## 备注



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// 在幻灯片中心左侧添加新的垂直绘图参考线
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 类 [LayoutSlide](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
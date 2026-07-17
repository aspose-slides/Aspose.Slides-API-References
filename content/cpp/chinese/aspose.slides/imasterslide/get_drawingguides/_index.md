---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 参考
description: 返回主幻灯片的绘图参考线集合。只读 IDrawingGuidesCollection
type: docs
weight: 105
url: /zh/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() 方法

返回主幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## 备注

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// 在幻灯片中心右侧添加新的垂直绘图参考线
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 类 [IMasterSlide](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
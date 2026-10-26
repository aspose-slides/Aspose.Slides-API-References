---
title: GetBasePlaceholder()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回基本的佔位符形狀（形狀來自版面配置和/或母片投影片，且為目前形狀所繼承的）。
type: docs
weight: 573
url: /zh-hant/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() 方法


傳回基本的佔位符形狀（從版面配置和/或母片投影片繼承而來的形狀）。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## 備註


如果目前的形狀未被繼承，將傳回 null。

```cpp
// 取得佔位符形狀的所有（母片/版面/投影片）動畫效果
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
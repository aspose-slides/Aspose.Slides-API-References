---
title: GetBasePlaceholder()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个基本的占位符形状（当前形状继承自的布局和/或母版幻灯片中的形状）。
type: docs
weight: 573
url: /zh/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() 方法

返回一个基本的占位符形状（当前形状继承自的布局和/或母版幻灯片中的形状）。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## 备注

如果当前形状没有被继承，则返回 null。

```cpp
// 获取占位符形状的所有（母版/版面/幻灯片）动画效果
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
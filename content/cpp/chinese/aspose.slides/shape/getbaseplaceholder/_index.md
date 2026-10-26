---
title: GetBasePlaceholder()
second_title: Aspose.Slides C++ API 参考
description: 返回一个基本的占位符形状（该形状来自布局和/或母版幻灯片，当前形状从中继承）。
type: docs
weight: 638
url: /zh/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() 方法


返回一个基本的占位符形状（该形状来自布局和/或母版幻灯片，当前形状从中继承）。

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## 备注


如果当前形状未被继承，则返回 null。


```cpp
// 获取占位符形状的所有（母版/布局/幻灯片）动画效果
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../../ishape/)
* 类 [Shape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)
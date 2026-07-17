---
title: set_AfterAnimationColor()
second_title: Aspose.Slides for C++ API 参考
description: 为效果定义后动画颜色。写入 IColorFormat。
type: docs
weight: 261
url: /zh/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) 方法

为效果定义后动画颜色。写入 [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IColorFormat](../../../aspose.slides/icolorformat/)
* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)
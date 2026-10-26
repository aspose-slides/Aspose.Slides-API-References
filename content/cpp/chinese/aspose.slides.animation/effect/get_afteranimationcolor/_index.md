---
title: get_AfterAnimationColor()
second_title: Aspose.Slides C++ API 参考
description: 为效果定义后动画颜色。阅读 IColorFormat.
type: docs
weight: 248
url: /zh/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() 方法

定义效果的后动画颜色。阅读 [IColorFormat](../../../aspose.slides/icolorformat/)。

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
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

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IColorFormat](../../../aspose.slides/icolorformat/)
* 类 [Effect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
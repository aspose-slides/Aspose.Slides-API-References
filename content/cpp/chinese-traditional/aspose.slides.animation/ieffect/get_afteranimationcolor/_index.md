---
title: get_AfterAnimationColor()
second_title: Aspose.Slides for C++ API 參考
description: 定義效果的後動畫顏色。請閱讀 IColorFormat.
type: docs
weight: 248
url: /zh-hant/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() 方法


定義效果的後動畫顏色。請閱讀 [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
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

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IColorFormat](../../../aspose.slides/icolorformat/)
* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)
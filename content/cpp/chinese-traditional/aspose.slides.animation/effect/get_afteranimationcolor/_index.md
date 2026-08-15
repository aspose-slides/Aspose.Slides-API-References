---
title: get_AfterAnimationColor()
second_title: Aspose.Slides C++ API 參考
description: 為效果定義動畫後的顏色。請閱讀 IColorFormat.
type: docs
weight: 248
url: /zh-hant/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() 方法


定義效果的動畫後顏色。請閱讀 [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IColorFormat](../../../aspose.slides/icolorformat/)
* 類別 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
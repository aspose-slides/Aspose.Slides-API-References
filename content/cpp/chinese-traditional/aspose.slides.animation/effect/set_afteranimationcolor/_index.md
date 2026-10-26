---
title: set_AfterAnimationColor()
second_title: Aspose.Slides C++ API 參考
description: 定義效果的動畫後顏色。寫入 IColorFormat.
type: docs
weight: 261
url: /zh-hant/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) 方法


定義效果的動畫後顏色。寫入 [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## 備註


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一張投影片的第一個效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 將效果的動畫後類型更改為「Color」
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// 設定效果的動畫後顏色。
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IColorFormat](../../../aspose.slides/icolorformat/)
* 類別 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)
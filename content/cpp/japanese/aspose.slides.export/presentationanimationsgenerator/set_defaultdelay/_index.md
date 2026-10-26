---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトの遅延時間を[ms]で設定します。
type: docs
weight: 14
url: /ja/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) method

デフォルトの遅延時間を[ms]で設定します。

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1秒
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 参照

* クラス [PresentationAnimationsGenerator](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトの遅延時間を取得します [ms]。
type: docs
weight: 1
url: /ja/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const メソッド


デフォルトの遅延時間を取得します [ms]。

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
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
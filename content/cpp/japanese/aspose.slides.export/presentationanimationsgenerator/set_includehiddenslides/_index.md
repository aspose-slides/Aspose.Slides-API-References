---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API リファレンス
description: 非表示スライドを含めるかどうかを取得または設定します。
type: docs
weight: 40
url: /ja/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) メソッド

非表示スライドを含めるかどうかを取得または設定します。

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 参照

* クラス [PresentationAnimationsGenerator](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)
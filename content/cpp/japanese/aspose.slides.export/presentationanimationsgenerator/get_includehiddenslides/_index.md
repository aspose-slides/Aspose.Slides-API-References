---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides の C++ API リファレンス
description: 非表示スライドを含めるかどうかを取得または設定します。
type: docs
weight: 27
url: /ja/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const メソッド


非表示スライドを含めるかどうかを取得または設定します。

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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
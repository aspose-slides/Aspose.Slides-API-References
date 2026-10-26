---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API 參考
description: 取得或設定是否應包含隱藏的投影片。
type: docs
weight: 27
url: /zh-hant/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const 方法


取得或設定是否應包含隱藏的投影片。

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 另請參閱

* 類別 [PresentationAnimationsGenerator](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)
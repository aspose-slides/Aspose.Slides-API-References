---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得或設定是否應包含隱藏投影片。
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) 方法

取得或設定是否應包含隱藏投影片。

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
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
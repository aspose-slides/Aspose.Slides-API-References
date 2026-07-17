---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API 参考
description: 获取或设置是否应包括隐藏的幻灯片。
type: docs
weight: 27
url: /zh/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const 方法


获取或设置是否应包含隐藏的幻灯片。

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// …
animationsGenerator->Run(presentation->get_Slides());
```




## 另请参见

* 类 [PresentationAnimationsGenerator](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)
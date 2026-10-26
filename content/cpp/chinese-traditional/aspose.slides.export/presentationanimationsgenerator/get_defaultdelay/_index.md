---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得預設延遲時間 [ms]。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const 方法

取得預設延遲時間 [ms]。

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1秒
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 另請參閱

* 類別 [PresentationAnimationsGenerator](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)
---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API 参考
description: 设置默认延迟时间 [ms]。
type: docs
weight: 14
url: /zh/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) 方法


设置默认延迟时间 [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1秒
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 另请参见

* 类 [PresentationAnimationsGenerator](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)
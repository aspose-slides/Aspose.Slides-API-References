---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API 参考
description: 获取默认延迟时间 [ms]。
type: docs
weight: 1
url: /zh/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const 方法


获取默认延迟时间 [ms]。

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1秒
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## 参见

* 类 [PresentationAnimationsGenerator](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)
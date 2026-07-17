---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API 参考
description: "设置默认延迟时间[ms]。如果未调用 ISlideShowTransition::set_AdvanceAfterTime() 方法，则使用此值。默认值为1000。"
type: docs
weight: 92
url: /zh/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) 方法

设置默认延迟时间[ms]。如果未调用[ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/)方法，则使用此值。默认值为1000。

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## 备注



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另见

* 类 [IGifOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)
---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API 参考
description: "获取默认延迟时间[毫秒]。如果未调用 ISlideShowTransition::set_AdvanceAfterTime() 方法，则使用此值。默认值为 1000。"
type: docs
weight: 79
url: /zh/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() 方法

获取默认延迟时间[毫秒]。如果未调用[ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/)方法，则使用此值。默认值为1000。

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## 备注

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另请参见

* 类 [IGifOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)
---
title: set_TransitionFps()
second_title: Aspose.Slides C++ API 参考
description: 设置过渡 FPS [frames/sec]。默认值为 25.
type: docs
weight: 66
url: /zh/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) 方法


设置过渡 FPS [frames/sec]。默认值为 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 另见

* 类 [IGifOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)
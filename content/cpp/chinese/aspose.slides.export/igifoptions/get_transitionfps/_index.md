---
title: get_TransitionFps()
second_title: Aspose.Slides C++ API 参考
description: 获取过渡帧率 [frames/sec]，默认值为 25.
type: docs
weight: 53
url: /zh/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() 方法

获取过渡帧率 [frames/sec]，默认值为 25。

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
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
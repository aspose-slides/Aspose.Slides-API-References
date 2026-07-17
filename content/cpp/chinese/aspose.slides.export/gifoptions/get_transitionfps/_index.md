---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API 参考
description: 获取过渡帧率 [帧/秒] 默认值为 25.
type: docs
weight: 53
url: /zh/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() 方法

获取过渡帧率 [帧/秒] 默认值为 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另见

* 类 [GifOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)
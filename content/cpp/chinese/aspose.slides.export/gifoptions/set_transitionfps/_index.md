---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API 参考
description: 设置转换帧率 FPS [frames/sec]。默认值为 25.
type: docs
weight: 66
url: /zh/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) 方法


设置转换帧率 FPS [frames/sec]。默认值为 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另请参见

* 类 [GifOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)
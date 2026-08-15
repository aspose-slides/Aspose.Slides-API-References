---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API 參考
description: 取得過渡 FPS [frames/sec]，預設值為 25。
type: docs
weight: 53
url: /zh-hant/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() 方法

取得過渡 FPS [frames/sec]。預設值為 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另見

* 類別 [IGifOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)
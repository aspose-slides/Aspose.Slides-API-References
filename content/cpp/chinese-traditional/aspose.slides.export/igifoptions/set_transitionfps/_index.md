---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API 參考
description: 設定過渡 FPS [frames/sec] 預設值為 25.
type: docs
weight: 66
url: /zh-hant/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) 方法


設定過渡 FPS [frames/sec] 預設值為 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 另請參閱

* 類別 [IGifOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)
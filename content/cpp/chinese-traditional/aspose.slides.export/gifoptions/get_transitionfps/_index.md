---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API 參考手冊
description: 取得過渡 FPS [frames/sec]。預設值為 25。
type: docs
weight: 53
url: /zh-hant/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() 方法


取得過渡 FPS [frames/sec]。預設值為 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另請參閱

* 類別 [GifOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)
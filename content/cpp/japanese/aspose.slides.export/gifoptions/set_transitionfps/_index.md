---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API リファレンス
description: 遷移のFPS [frames/sec] を設定します。デフォルト値は25です。
type: docs
weight: 66
url: /ja/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) メソッド


遷移のFPS [frames/sec] を設定します。デフォルト値は 25 です。

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 参照

* クラス [GifOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)
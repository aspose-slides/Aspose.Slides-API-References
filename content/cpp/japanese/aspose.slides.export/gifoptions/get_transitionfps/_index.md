---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API リファレンス
description: 遷移 FPS を取得します [frames/sec] デフォルト値は 25 です。
type: docs
weight: 53
url: /ja/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() メソッド


遷移 FPS を取得します [frames/sec] デフォルト値は 25 です。

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
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
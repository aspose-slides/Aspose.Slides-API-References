---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API リファレンス
description: 遷移FPS [frames/sec] を取得します。デフォルト値は25です。
type: docs
weight: 53
url: /ja/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() メソッド

遷移FPS [frames/sec] を取得します。デフォルト値は25です。

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## See Also

* クラス [IGifOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)
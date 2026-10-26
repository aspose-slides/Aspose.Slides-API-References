---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API リファレンス
description: 遷移FPS[frames/sec]を設定します。デフォルト値は25です。
type: docs
weight: 66
url: /ja/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) メソッド


遷移FPS[frames/sec]を設定します。デフォルト値は25です。

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 参照

* クラス [IGifOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)
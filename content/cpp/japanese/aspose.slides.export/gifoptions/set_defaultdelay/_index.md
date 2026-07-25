---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API リファレンス
description: "デフォルトの遅延時間を[ms]で設定します。この値は ISlideShowTransition::set_AdvanceAfterTime() メソッドが呼び出されなかった場合に使用されます。デフォルト値は1000です。"
type: docs
weight: 92
url: /ja/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) メソッド


デフォルトの遅延時間を[ms]で設定します。この値は[ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) メソッドが呼び出されなかった場合に使用されます。デフォルト値は1000です。

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 参照

* クラス [GifOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)
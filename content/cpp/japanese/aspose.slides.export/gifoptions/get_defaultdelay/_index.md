---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API リファレンス
description: "デフォルトの遅延時間を取得します [ms]。この値は ISlideShowTransition::set_AdvanceAfterTime() メソッドが呼び出されなかった場合に使用されます。デフォルト値は 1000 です。"
type: docs
weight: 79
url: /ja/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() メソッド

デフォルトの遅延時間を取得します [ms]。この値は [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) メソッドが呼び出されなかった場合に使用されます。デフォルト値は 1000 です。

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 関連項目

* クラス [GifOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)
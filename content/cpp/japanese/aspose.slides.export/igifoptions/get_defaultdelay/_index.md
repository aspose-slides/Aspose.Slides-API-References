---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API リファレンス
description: "デフォルトの遅延時間 [ms] を取得します。この値は ISlideShowTransition::set_AdvanceAfterTime() メソッドが呼び出されなかった場合に使用されます。デフォルト値は 1000 です。"
type: docs
weight: 79
url: /ja/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() メソッド


デフォルトの遅延時間 [ms] を取得します。この値は [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) メソッドが呼び出されなかった場合に使用されます。デフォルト値は 1000 です。

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 参照

* クラス [IGifOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)
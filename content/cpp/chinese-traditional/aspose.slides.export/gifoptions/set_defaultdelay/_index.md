---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API 參考
description: "設定預設延遲時間 [ms]。如果未呼叫 ISlideShowTransition::set_AdvanceAfterTime() 方法，將使用此值。預設值為 1000。"
type: docs
weight: 92
url: /zh-hant/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) 方法


設定預設延遲時間[毫秒]。如果未呼叫 [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) 方法，將使用此值。預設值為 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 另請參閱

* 類別 [GifOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)
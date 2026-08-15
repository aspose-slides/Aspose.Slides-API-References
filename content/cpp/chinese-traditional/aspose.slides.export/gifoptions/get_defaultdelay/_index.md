---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API 參考文件
description: "取得預設延遲時間 [ms]。如果未呼叫 ISlideShowTransition::set_AdvanceAfterTime() 方法，將使用此值。預設值為 1000."
type: docs
weight: 79
url: /zh-hant/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() 方法


取得預設延遲時間 [ms]。如果未呼叫 [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) 方法，將使用此值。預設值為 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 參見

* 類別 [GifOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)
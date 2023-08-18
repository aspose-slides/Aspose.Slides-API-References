---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API Reference
description: "Gets default delay time [ms]. This value will be used if the ISlideShowTransition::set_AdvanceAfterTime() method was not called. The default value is 1000."
type: docs
weight: 79
url: /aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() method


Gets default delay time [ms]. This value will be used if the [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) method was not called. The default value is 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Remarks



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## See Also

* Class [GifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
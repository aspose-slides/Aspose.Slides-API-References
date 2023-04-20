---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API Reference
description: "Gets default delay time [ms]. This value will be used if the ISlideShowTransition::set_AdvanceAfterTime() method was not called. The default value is 1000."
type: docs
weight: 79
url: /cpp/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() method


Gets default delay time [ms]. This value will be used if the [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) method was not called. The default value is 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Remarks



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## See Also

* Class [IGifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
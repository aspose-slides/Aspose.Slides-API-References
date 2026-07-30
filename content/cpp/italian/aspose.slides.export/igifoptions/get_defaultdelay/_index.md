---
title: get_DefaultDelay()
second_title: Riferimento API di Aspose.Slides per C++
description: "Recupera il tempo di ritardo predefinito [ms]. Questo valore sarà utilizzato se il metodo ISlideShowTransition::set_AdvanceAfterTime() non è stato chiamato. Il valore predefinito è 1000."
type: docs
weight: 79
url: /it/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() metodo


Recupera il tempo di ritardo predefinito [ms]. Questo valore sarà utilizzato se il [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) metodo non è stato chiamato. Il valore predefinito è 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Note



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Vedi anche

* Classe [IGifOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)
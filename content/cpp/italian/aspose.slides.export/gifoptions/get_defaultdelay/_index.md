---
title: get_DefaultDelay()
second_title: Riferimento API Aspose.Slides per C++
description: "Restituisce il tempo di ritardo predefinito [ms]. Questo valore verrà utilizzato se il metodo ISlideShowTransition::set_AdvanceAfterTime() non è stato chiamato. Il valore predefinito è 1000."
type: docs
weight: 79
url: /it/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() metodo


Restituisce il tempo di ritardo predefinito [ms]. Questo valore verrà utilizzato se il metodo [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) non è stato chiamato. Il valore predefinito è 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Vedi anche

* Classe [GifOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)
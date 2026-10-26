---
title: set_DefaultDelay()
second_title: Riferimento API Aspose.Slides per C++
description: "Imposta il tempo di ritardo predefinito [ms]. Questo valore verrà utilizzato se il metodo ISlideShowTransition::set_AdvanceAfterTime() non è stato chiamato. Il valore predefinito è 1000."
type: docs
weight: 92
url: /it/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) metodo


Imposta il tempo di ritardo predefinito [ms]. Questo valore verrà utilizzato se il metodo [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) non è stato chiamato. Il valore predefinito è 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## Osservazioni



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
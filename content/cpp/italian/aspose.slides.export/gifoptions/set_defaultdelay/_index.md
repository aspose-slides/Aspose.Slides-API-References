---
title: set_DefaultDelay()
second_title: Riferimento API Aspose.Slides per C++
description: "Imposta il tempo di ritardo predefinito [ms]. Questo valore verrà utilizzato se il metodo ISlideShowTransition::set_AdvanceAfterTime() non è stato chiamato. Il valore predefinito è 1000."
type: docs
weight: 92
url: /it/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) metodo

Imposta il tempo di ritardo predefinito [ms]. Questo valore verrà utilizzato se il [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) metodo non è stato chiamato. Il valore predefinito è 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
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
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)
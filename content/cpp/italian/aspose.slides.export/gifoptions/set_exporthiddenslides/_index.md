---
title: set_ExportHiddenSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se le diapositive nascoste saranno esportate. Il valore predefinito è false.
type: docs
weight: 40
url: /it/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) metodo


Determina se le diapositive nascoste saranno esportate. Il valore predefinito è false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Vedi anche

* Classe [GifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)
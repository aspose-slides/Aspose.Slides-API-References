---
title: get_ExportHiddenSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se le diapositive nascoste saranno esportate. Il valore predefinito è false.
type: docs
weight: 27
url: /it/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() metodo


Determina se le diapositive nascoste saranno esportate. Il valore predefinito è false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Osservazioni


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```


## Vedi anche

* Classe [IGifOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)
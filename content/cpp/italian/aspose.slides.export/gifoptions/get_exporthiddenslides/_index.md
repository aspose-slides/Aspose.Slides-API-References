---
title: get_ExportHiddenSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se le diapositive nascoste verranno esportate. Il valore predefinito è false.
type: docs
weight: 27
url: /it/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() metodo


Determina se le diapositive nascoste verranno esportate. Il valore predefinito è false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Note



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Vedi anche

* Classe [GifOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)
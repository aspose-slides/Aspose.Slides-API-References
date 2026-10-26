---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides per il riferimento API C++
description: Determina se le diapositive nascoste saranno esportate. Il valore predefinito è false.
type: docs
weight: 40
url: /it/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) metodo

Determina se le diapositive nascoste saranno esportate. Il valore predefinito è false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
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
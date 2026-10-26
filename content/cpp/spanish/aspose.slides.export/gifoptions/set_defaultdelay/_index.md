---
title: set_DefaultDelay()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Establece el tiempo de retardo predeterminado [ms]. Este valor se usará si no se llamó al método ISlideShowTransition::set_AdvanceAfterTime(). El valor predeterminado es 1000."
type: docs
weight: 92
url: /es/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) método


Establece el tiempo de retardo predeterminado [ms]. Este valor se usará si el método [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) no fue llamado. El valor predeterminado es 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Véase también

* Clase [GifOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)
---
title: get_DefaultDelay()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el tiempo de retardo predeterminado [ms]. Este valor se utilizará si el método ISlideShowTransition::set_AdvanceAfterTime() no fue llamado. El valor predeterminado es 1000."
type: docs
weight: 79
url: /es/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() método


Obtiene el tiempo de retardo predeterminado [ms]. Este valor se usará si el método [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) no fue llamado. El valor predeterminado es 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Ver también

* Clase [GifOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)
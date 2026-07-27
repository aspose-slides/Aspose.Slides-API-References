---
title: get_DefaultDelay()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el tiempo de retardo predeterminado [ms]. Este valor se usará si no se llamó al método ISlideShowTransition::set_AdvanceAfterTime(). El valor predeterminado es 1000."
type: docs
weight: 79
url: /es/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() método

Obtiene el tiempo de retardo predeterminado [ms]. Este valor se usará si no se llamó al método [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). El valor predeterminado es 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Ver también

* Clase [IGifOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)
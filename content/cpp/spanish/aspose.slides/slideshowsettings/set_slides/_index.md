---
title: set_Slides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Rango de diapositivas
type: docs
weight: 131
url: /es/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) método


[Slides](../../) rango

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [SlidesRange](../../slidesrange/)
* Clase [SlideShowSettings](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
---
title: get_Slides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Rango de diapositivas
type: docs
weight: 118
url: /es/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const método

[Slides](../../) rango

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
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
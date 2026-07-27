---
title: get_TargetSection()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el objeto de sección al que está vinculado el objeto Section Zoom. Lea ISection.
type: docs
weight: 1
url: /es/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() método


Obtiene el objeto de sección al que está vinculado el objeto Zoom [Section](../../section/). Lea [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Observaciones


Este ejemplo muestra cómo cambiar la sección de destino y crea una nueva imagen para el objeto de zoom de sección: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISection](../../isection/)
* Clase [ISectionZoomFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
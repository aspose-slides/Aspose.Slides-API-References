---
title: set_TargetSection()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el objeto de sección al que está vinculado el objeto Section Zoom. Escriba ISection.
type: docs
weight: 14
url: /es/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) método

Establece el objeto de sección al que está vinculado el objeto Zoom [Section](../../section/). Escriba [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Observaciones

Este ejemplo demuestra cambiar la sección objetivo y crea una nueva imagen para el objeto zoom de sección: 
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
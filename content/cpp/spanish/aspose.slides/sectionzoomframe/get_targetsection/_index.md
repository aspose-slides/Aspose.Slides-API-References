---
title: get_TargetSection()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el objeto de sección al que el objeto Section Zoom enlaza. Lea ISection.
type: docs
weight: 1
url: /es/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() método


Obtiene el objeto de sección al que el objeto Zoom [Section](../../section/) enlaza. Lea [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Observaciones


El siguiente ejemplo muestra cómo cambiar la sección objetivo y crea una nueva imagen para el objeto de zoom de sección: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISection](../../isection/)
* Clase [SectionZoomFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
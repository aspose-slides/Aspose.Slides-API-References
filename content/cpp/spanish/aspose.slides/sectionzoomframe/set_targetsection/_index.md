---
title: set_TargetSection()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el objeto de sección al que enlaza el objeto Section Zoom. Escribe ISection.
type: docs
weight: 14
url: /es/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) método

Establece el objeto de sección al que enlaza el objeto [Section](../../section/) Zoom. Escribe [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Comentarios

El siguiente ejemplo demuestra cómo cambiar la sección de destino y crea una nueva imagen para el objeto de zoom de sección: 
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
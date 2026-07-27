---
title: get_DrawingGuides()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la colección de las guías de dibujo. Solo lectura IDrawingGuidesCollection
type: docs
weight: 53
url: /es/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() método

Devuelve la colección de las guías de dibujo. Solo lectura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Observaciones

El siguiente código de ejemplo muestra cómo agregar las nuevas guías de dibujo en una presentación de PowerPoint. ```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Agregar la nueva guía de dibujo vertical a la derecha del centro de la diapositiva
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Agregar la nueva guía de dibujo horizontal debajo del centro de la diapositiva
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Clase [CommonSlideViewProperties](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
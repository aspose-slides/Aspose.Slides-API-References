---
title: get_DrawingGuides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una colección de guías de dibujo para la diapositiva de diseño. Solo lectura IDrawingGuidesCollection
type: docs
weight: 79
url: /es/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() método


Devuelve una colección de guías de dibujo para la diapositiva de diseño. Solo lectura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## Observaciones


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Añadiendo la nueva guía de dibujo vertical a la izquierda del centro de la diapositiva
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Clase [ILayoutSlide](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
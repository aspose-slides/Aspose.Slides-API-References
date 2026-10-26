---
title: get_DrawingGuides()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una colección de guías de dibujo para la diapositiva de diseño. Solo lectura IDrawingGuidesCollection
type: docs
weight: 118
url: /es/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() método


Devuelve una colección de guías de dibujo para la diapositiva de diseño. Solo lectura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```


## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Agregando la nueva guía de dibujo vertical a la izquierda del centro de la diapositiva
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Clase [LayoutSlide](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: get_DrawingGuides()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una colección de guías de dibujo para la diapositiva maestra. Solo lectura IDrawingGuidesCollection
type: docs
weight: 170
url: /es/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() método


Devuelve una colección de guías de dibujo para la diapositiva maestra. Solo lectura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Agregar la nueva guía de dibujo vertical a la derecha del centro de la diapositiva
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```


## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Clase [MasterSlide](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
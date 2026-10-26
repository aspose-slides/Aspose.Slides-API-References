---
title: get_DrawingGuides()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una collezione di guide di disegno per la diapositiva master. Sola lettura IDrawingGuidesCollection
type: docs
weight: 170
url: /it/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() metodo

Restituisce una collezione di guide di disegno per la diapositiva master. Sola lettura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Osservazioni

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Aggiunta della nuova guida di disegno verticale a destra del centro della diapositiva
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [MasterSlide](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
---
title: get_DrawingGuides()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la collezione delle guide di disegno. Sola lettura IDrawingGuidesCollection
type: docs
weight: 53
url: /it/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() metodo

Restituisce la collezione delle guide di disegno. Sola lettura [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Osservazioni

Il seguente codice di esempio mostra come aggiungere le nuove guide di disegno in una presentazione PowerPoint. ```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Adding the new vertical drawing guide to the right of the slide center
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Classe [ICommonSlideViewProperties](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
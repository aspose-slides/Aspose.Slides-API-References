---
title: set_TileAlignment()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta come la trama è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del modello di trama e come si ripete lungo la forma. Scrivi RectangleAlignment.
type: docs
weight: 391
url: /it/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) metodo

Imposta come la trama è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del modello di trama e come si ripete lungo la forma. Scrivi [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Osservazioni

Il valore predefinito è [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta l'allineamento delle piastrelle in basso a destra
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Vedi anche

* Enum [RectangleAlignment](../../rectanglealignment/)
* Classe [PictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
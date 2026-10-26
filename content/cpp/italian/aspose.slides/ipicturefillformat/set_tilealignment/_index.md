---
title: set_TileAlignment()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta come la texture è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del modello di texture e come questa si ripete sulla forma. Scrivi RectangleAlignment.
type: docs
weight: 391
url: /it/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) metodo


Imposta come la texture è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del modello di texture e come questa si ripete sulla forma. Scrivi [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
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

// Imposta l'allineamento per la piastrellatura in basso a destra
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Vedi anche

* Enum [RectangleAlignment](../../rectanglealignment/)
* Classe [IPictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
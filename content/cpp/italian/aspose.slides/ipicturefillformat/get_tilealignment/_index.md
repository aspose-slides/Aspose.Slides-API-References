---
title: get_TileAlignment()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce come la trama è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del modello di trama e come si ripete sulla forma. Leggi RectangleAlignment.
type: docs
weight: 378
url: /it/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() metodo

Restituisce come la trama è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del modello di trama e come si ripete sulla forma. Leggi [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
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

// Imposta l'allineamento del tassellamento in basso a destra
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Vedi anche

* Enum [RectangleAlignment](../../rectanglealignment/)
* Classe [IPictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
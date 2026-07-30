---
title: get_TileAlignment()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce come la texture è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del motivo della texture e come si ripete nella forma. Leggi RectangleAlignment.
type: docs
weight: 378
url: /it/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() metodo

Restituisce come la texture è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del pattern della texture e come si ripete nella forma. Leggi [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
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

// Imposta l'allineamento per il mosaico in basso a destra
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Vedi anche

* Enum [RectangleAlignment](../../rectanglealignment/)
* Classe [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
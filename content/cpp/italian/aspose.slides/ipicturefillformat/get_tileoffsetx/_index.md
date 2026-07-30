---
title: get_TileOffsetX()
second_title: Aspose.Slides per l'API di riferimento C++
description: Restituisce l'offset orizzontale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso destra, mentre un valore negativo la sposta verso sinistra. Leggi float.
type: docs
weight: 274
url: /it/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() metodo

Restituisce l'offset orizzontale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso destra, mentre un valore negativo la sposta verso sinistra. Leggi **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Osservazioni

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta l'offset orizzontale della texture a 20 punti
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Vedi anche

* Classe [IPictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
---
title: get_TileOffsetY()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'offset verticale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso il basso, mentre un valore negativo la sposta verso l'alto. Leggi float.
type: docs
weight: 300
url: /it/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() metodo

Restituisce l'offset verticale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso il basso, mentre un valore negativo la sposta verso l'alto. Leggi **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta l'offset verticale della texture a -50 punti
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Vedi anche

* Classe [IPictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
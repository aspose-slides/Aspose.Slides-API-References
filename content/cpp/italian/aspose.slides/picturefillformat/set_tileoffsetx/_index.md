---
title: set_TileOffsetX()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta lo spostamento orizzontale della trama rispetto all'origine della forma in punti. Un valore positivo sposta la trama verso destra, mentre un valore negativo la sposta verso sinistra. Scrivi float.
type: docs
weight: 287
url: /it/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) metodo

Imposta lo spostamento orizzontale della trama rispetto all'origine della forma in punti. Un valore positivo sposta la trama verso destra, mentre un valore negativo la sposta verso sinistra. Scrivi **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta lo spostamento orizzontale della trama a 20 punti
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Vedi anche

* Classe [PictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
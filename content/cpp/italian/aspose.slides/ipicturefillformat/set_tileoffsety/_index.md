---
title: set_TileOffsetY()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta lo spostamento verticale della trama rispetto all'origine della forma in punti. Un valore positivo sposta la trama verso il basso, mentre un valore negativo la sposta verso l'alto. Scrivi float.
type: docs
weight: 313
url: /it/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) metodo


Imposta lo spostamento verticale della trama rispetto all'origine della forma in punti. Un valore positivo sposta la trama verso il basso, mentre un valore negativo la sposta verso l'alto. Scrivi **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta lo spostamento verticale della trama a -50 punti
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Vedi anche

* Classe [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
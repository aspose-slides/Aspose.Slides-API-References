---
title: get_TileOffsetY()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'offset verticale della trama rispetto all'origine della forma, espresso in punti. Un valore positivo sposta la trama verso il basso, mentre un valore negativo la sposta verso l'alto. Leggi float.
type: docs
weight: 300
url: /it/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() metodo


Restituisce l'offset verticale della trama rispetto all'origine della forma, espresso in punti. Un valore positivo sposta la trama verso il basso, mentre un valore negativo la sposta verso l'alto. Leggi **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta l'offset verticale della trama a -50 punti
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Vedi anche

* Classe [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
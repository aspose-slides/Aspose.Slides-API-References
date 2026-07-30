---
title: get_TileScaleX()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la scala orizzontale per il riempimento con trama come percentuale. Lettura float.
type: docs
weight: 326
url: /it/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() metodo

Restituisce la scala orizzontale per il riempimento con trama come percentuale. Lettura **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta la scala orizzontale della trama al 120 percento
pictureFillFormat->set_TileScaleX(120.0f);
```

## Vedi anche

* Classe [IPictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
---
title: get_TileScaleX()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la scala orizzontale del riempimento texture come percentuale. Leggi float.
type: docs
weight: 326
url: /it/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() metodo


Restituisce la scala orizzontale del riempimento texture come percentuale. Leggi **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta la scala orizzontale della texture al 120 percento
pictureFillFormat->set_TileScaleX(120.0f);
```

## Vedi anche

* Classe [PictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
---
title: get_TileScaleY()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la scala verticale per il riempimento texture come percentuale. Leggi float.
type: docs
weight: 352
url: /it/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() metodo


Restituisce la scala verticale per il riempimento texture come percentuale. Leggi **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta la scala verticale per la texture a 120 percento
pictureFillFormat->set_TileScaleY(120.0f);
```

## Vedi anche

* Classe [PictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
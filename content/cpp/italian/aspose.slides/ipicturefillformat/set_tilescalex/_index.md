---
title: set_TileScaleX()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la scala orizzontale del riempimento texture come percentuale. Scrivi float.
type: docs
weight: 339
url: /it/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) metodo

Imposta la scala orizzontale del riempimento texture come percentuale. Scrivi **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
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

* Classe [IPictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
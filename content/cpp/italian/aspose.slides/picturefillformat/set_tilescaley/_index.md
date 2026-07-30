---
title: set_TileScaleY()
second_title: Aspose.Slides per C++ Riferimento API
description: Imposta la scala verticale per il riempimento della trama come percentuale. Scrivi float.
type: docs
weight: 365
url: /it/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) metodo

Imposta la scala verticale per il riempimento della trama come percentuale. Scrivi **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Osservazioni


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Imposta la scala verticale per la trama al 120 percento
pictureFillFormat->set_TileScaleY(120.0f);
```

## Vedi anche

* Classe [PictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
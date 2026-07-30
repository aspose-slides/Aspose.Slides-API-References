---
title: get_TileFlip()
second_title: Riferimento API Aspose.Slides per C++
description: "Capovolge la tessera della texture attorno al suo asse orizzontale, verticale o a entrambi gli assi. Leggi Slides::TileFlip."
type: docs
weight: 404
url: /it/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() metodo


Capovolge la tessera della texture attorno al suo asse orizzontale, verticale o entrambi. Leggi [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Osservazioni


Il valore predefinito è [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Capovolge la tessera della texture attorno al suo asse verticale.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Vedi anche

* Enum [TileFlip](../../tileflip/)
* Classe [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
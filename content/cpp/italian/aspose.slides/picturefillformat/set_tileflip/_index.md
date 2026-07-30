---
title: set_TileFlip()
second_title: Riferimento API di Aspose.Slides per C++
description: "Capovolge la tessera di texture attorno al suo asse orizzontale, verticale o a entrambi gli assi. Scrivi Slides::TileFlip."
type: docs
weight: 417
url: /it/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) method


Capovolge la tessera di texture attorno al suo asse orizzontale, verticale o a entrambi gli assi. Scrivi [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Note


Il valore predefinito è [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il formato di riempimento immagine della forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Imposta la modalità di riempimento immagine su Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Capovolge la tessera di texture attorno al suo asse verticale.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Vedi anche

* Enum [TileFlip](../../tileflip/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
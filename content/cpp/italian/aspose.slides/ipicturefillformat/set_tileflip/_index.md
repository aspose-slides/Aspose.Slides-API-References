---
title: set_TileFlip()
second_title: Riferimento API di Aspose.Slides per C++
description: "Capovolge la piastrella di texture attorno al suo asse orizzontale, verticale o a entrambi gli assi. Scrivi Slides::TileFlip."
type: docs
weight: 417
url: /it/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) method


Capovolge la piastrella di texture attorno al suo asse orizzontale, verticale o a entrambi gli assi. Scrivi [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
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

// Capovolge la piastrella di texture attorno al suo asse verticale.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Vedi anche

* Enum [TileFlip](../../tileflip/)
* Classe [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
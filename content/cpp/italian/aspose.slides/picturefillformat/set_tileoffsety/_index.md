---
title: set_TileOffsetY()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta lo spostamento verticale della texture rispetto all'origine della forma in punti. Un valore positivo sposta la texture verso il basso, mentre un valore negativo la sposta verso l'alto. Scrivi float.
type: docs
weight: 313
url: /it/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) metodo


Imposta lo spostamento verticale della texture rispetto all'origine della forma in punti. Un valore positivo sposta la texture verso il basso, mentre un valore negativo la sposta verso l'alto. Scrivi **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the vertical offset of the texture to -50 points
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Vedi anche

* Classe [PictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
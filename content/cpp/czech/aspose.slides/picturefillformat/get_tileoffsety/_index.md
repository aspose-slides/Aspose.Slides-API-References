---
title: get_TileOffsetY()
second_title: Aspose.Slides pro C++ reference API
description: Vrací vertikální posun textury od počátku tvary v bodech. Kladná hodnota posune texturu dolů, zatímco záporná hodnota ji posune nahoru. Číst float.
type: docs
weight: 300
url: /cs/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() metoda


Vrací vertikální posun textury od počátku tvaru v bodech. Kladná hodnota posune texturu dolů, zatímco záporná hodnota ji posune nahoru. Číst **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá picture fill format tvaru
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Nastaví picture fill mode na Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Nastaví vertikální posun textury na -50 bodů
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Viz také

* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
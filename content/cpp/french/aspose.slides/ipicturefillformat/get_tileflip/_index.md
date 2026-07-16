---
title: get_TileFlip()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Retourne le fragment de texture autour de son axe horizontal, vertical ou les deux. Lire Slides::TileFlip."
type: docs
weight: 404
url: /fr/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() méthode

Retourne le fragment de texture autour de son axe horizontal, vertical ou les deux. Lire [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Remarques

La valeur par défaut est [TileFlip::NoFlip](../../tileflip/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Retourne le fragment de texture autour de son axe vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Voir aussi

* Enum [TileFlip](../../tileflip/)
* Classe [IPictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
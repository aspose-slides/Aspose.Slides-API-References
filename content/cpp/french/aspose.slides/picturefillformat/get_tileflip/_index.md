---
title: get_TileFlip()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Lire Slides::TileFlip."
type: docs
weight: 404
url: /fr/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() méthode


Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Lire [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
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

// Retourne la tuile de texture autour de son axe vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Voir aussi

* Enum [TileFlip](../../tileflip/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
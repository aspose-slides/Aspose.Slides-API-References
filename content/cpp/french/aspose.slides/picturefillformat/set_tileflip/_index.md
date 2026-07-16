---
title: set_TileFlip()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Fait pivoter la tuile de texture autour de son axe horizontal, vertical ou les deux. Écrivez Slides::TileFlip."
type: docs
weight: 417
url: /fr/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) méthode

Fait pivoter la tuile de texture autour de son axe horizontal, vertical ou les deux. Écrivez [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Remarques

La valeur par défaut est [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Récupère le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Fait pivoter la tuile de texture autour de son axe vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Voir aussi

* Énum [TileFlip](../../tileflip/)
* Classe [PictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
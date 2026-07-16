---
title: set_TileFlip()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Écrivez Slides::TileFlip."
type: docs
weight: 417
url: /fr/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) méthode


Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Écrivez [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Remarques


Par défaut [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Retourne la tuile de texture autour de son axe vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Voir aussi

* Enum [TileFlip](../../tileflip/)
* Classe [IPictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
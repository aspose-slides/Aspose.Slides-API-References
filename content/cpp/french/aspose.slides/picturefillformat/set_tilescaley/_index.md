---
title: set_TileScaleY()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'échelle verticale pour le remplissage de texture en pourcentage. Écrire float.
type: docs
weight: 365
url: /fr/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) méthode


Définit l'échelle verticale pour le remplissage de texture en pourcentage. Écrire **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Remarques



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit l'échelle verticale de la texture à 120 pourcents
pictureFillFormat->set_TileScaleY(120.0f);
```

## Voir aussi

* Classe [PictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: set_TileOffsetX()
second_title: Référence API Aspose.Slides pour C++
description: Définit le décalage horizontal de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Écrire float.
type: docs
weight: 287
url: /fr/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) méthode


Définit le décalage horizontal de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Écrire **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Remarques


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit le décalage horizontal de la texture à 20 points
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Voir aussi

* Classe [PictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
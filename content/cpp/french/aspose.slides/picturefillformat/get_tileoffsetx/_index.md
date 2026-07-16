---
title: get_TileOffsetX()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le décalage horizontal de la texture par rapport à l'origine de la forme, en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Lecture float.
type: docs
weight: 274
url: /fr/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() méthode

Renvoie le décalage horizontal de la texture par rapport à l'origine de la forme, en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Lecture **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
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
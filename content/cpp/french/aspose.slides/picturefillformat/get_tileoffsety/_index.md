---
title: get_TileOffsetY()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lire float.
type: docs
weight: 300
url: /fr/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() méthode

Renvoie le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lire **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Remarques

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit le décalage vertical de la texture à -50 points
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Voir aussi

* Classe [PictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
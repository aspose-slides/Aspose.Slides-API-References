---
title: get_TileOffsetY()
second_title: Aspose.Slides pour C++ Référence d'API
description: Renvoie le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture float.
type: docs
weight: 300
url: /fr/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() méthode


Renvoie le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
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

* Classe [IPictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
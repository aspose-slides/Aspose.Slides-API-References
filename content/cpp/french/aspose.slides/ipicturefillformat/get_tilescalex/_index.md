---
title: get_TileScaleX()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie l'échelle horizontale du remplissage de texture en pourcentage. Lecture float.
type: docs
weight: 326
url: /fr/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() méthode


Renvoie l'échelle horizontale du remplissage de texture en pourcentage. Lecture **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit l'échelle horizontale de la texture à 120 pourcents
pictureFillFormat->set_TileScaleX(120.0f);
```

## Voir aussi

* Classe [IPictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
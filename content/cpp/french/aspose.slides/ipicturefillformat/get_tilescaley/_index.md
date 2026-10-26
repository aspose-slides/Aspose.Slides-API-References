---
title: get_TileScaleY()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'échelle verticale du remplissage de texture en pourcentage. Lecture float.
type: docs
weight: 352
url: /fr/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() méthode

Renvoie l'échelle verticale du remplissage de texture en pourcentage. Lecture **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit l'échelle verticale de la texture à 120 pour cent
pictureFillFormat->set_TileScaleY(120.0f);
```

## Voir aussi

* Classe [IPictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
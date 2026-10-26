---
title: set_TileScaleX()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'échelle horizontale du remplissage de la texture en pourcentage. Écrivez float.
type: docs
weight: 339
url: /fr/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) méthode

Définit l'échelle horizontale du remplissage de la texture en pourcentage. Écrivez **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## Remarques



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit l'échelle horizontale de la texture à 120 pour cent
pictureFillFormat->set_TileScaleX(120.0f);
```

## Voir aussi

* Classe [PictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
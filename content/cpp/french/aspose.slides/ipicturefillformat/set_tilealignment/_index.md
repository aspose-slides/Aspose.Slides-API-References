---
title: set_TileAlignment()
second_title: Référence API Aspose.Slides pour C++
description: Définit comment la texture est alignée à l'intérieur de la forme. Ce réglage contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Écrivez RectangleAlignment.
type: docs
weight: 391
url: /fr/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) méthode


Définit la façon dont la texture est alignée à l'intérieur de la forme. Ce réglage contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Écrivez [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Remarques


La valeur par défaut est [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tuile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit l'alignement du carrelage en bas à droite
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Voir aussi

* Énum [RectangleAlignment](../../rectanglealignment/)
* Classe [IPictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
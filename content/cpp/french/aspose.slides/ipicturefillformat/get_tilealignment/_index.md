---
title: get_TileAlignment()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne la façon dont la texture est alignée dans la forme. Ce réglage contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Lire RectangleAlignment.
type: docs
weight: 378
url: /fr/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() méthode

Retourne la façon dont la texture est alignée dans la forme. Ce réglage contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Lire [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Remarques

Par défaut, c’est [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit l'alignement du carrelage sur BottomRight
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Voir aussi

* Enum [RectangleAlignment](../../rectanglealignment/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
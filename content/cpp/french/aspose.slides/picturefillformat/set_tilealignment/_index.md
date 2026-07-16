---
title: set_TileAlignment()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit comment la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Écrivez RectangleAlignment.
type: docs
weight: 391
url: /fr/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) méthode

Définit comment la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Écrivez [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Remarques

La valeur par défaut est [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le format de remplissage d'image de la forme
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Définit le mode de remplissage d'image sur Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Définit l'alignement du carrelage en bas à droite
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Voir aussi

* Enum [RectangleAlignment](../../rectanglealignment/)
* Classe [PictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
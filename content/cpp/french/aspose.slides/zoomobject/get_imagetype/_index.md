---
title: get_ImageType()
second_title: Référence API Aspose.Slides pour C++
description: "Obtient le type d'image d'un objet zoom. Lire ZoomImageType. Valeur par défaut : Preview"
type: docs
weight: 1
url: /fr/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() méthode

Obtient le type d'image d'un objet zoom. Lire [ZoomImageType](../../zoomimagetype/). Valeur par défaut : Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Remarques

Spécifie si l'objet Zoom utilise l'aperçu de la diapositive ou une image de couverture. 

L'exemple suivant montre comment changer le type d'image à la valeur Preview. Dans ce cas, l'image actuelle d'un objet Zoom passe à l'image de la diapositive : 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Voir aussi

* Enum [ZoomImageType](../../zoomimagetype/)
* Classe [ZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
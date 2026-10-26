---
title: set_ImageType()
second_title: Référence API Aspose.Slides pour C++
description: "Définit le type d’image d’un objet zoom. Écrivez ZoomImageType. Valeur par défaut : Preview"
type: docs
weight: 14
url: /fr/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) méthode


Définit le type d’image d’un objet zoom. Écrivez [ZoomImageType](../../zoomimagetype/). Valeur par défaut : Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Remarques


Spécifie si l’objet Zoom utilise l’aperçu de diapositive ou une image de couverture. 

Cet exemple montre comment changer le type d’image en valeur Preview. Dans ce cas, l’image actuelle d’un objet Zoom change en image de diapositive : 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Voir aussi

* Énumération [ZoomImageType](../../zoomimagetype/)
* Classe [IZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
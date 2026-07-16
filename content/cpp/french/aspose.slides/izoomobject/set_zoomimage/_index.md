---
title: set_ZoomImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'image pour l'objet de zoom. Écrivez IPPImage.
type: docs
weight: 92
url: /fr/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) méthode

Définit l'image pour l'objet de zoom. Écrivez [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## Remarques

L'exemple montre comment modifier l'image d'un objet Zoom : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [IZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
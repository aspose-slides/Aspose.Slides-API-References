---
title: get_ZoomImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient l'image pour l'objet zoom. Lire IPPImage.
type: docs
weight: 79
url: /fr/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() méthode


Obtient l'image pour l'objet Zoom. Lire [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Remarques


L'exemple montre comment changer l'image d'un objet Zoom : 
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
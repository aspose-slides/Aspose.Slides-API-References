---
title: get_ZoomImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient l'image de l'objet Zoom. Lire IPPImage.
type: docs
weight: 79
url: /fr/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() méthode

Obtient l'image de l'objet Zoom. Lire [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Remarques

L'exemple montre comment changer l'image d'un objet Zoom:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [ZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
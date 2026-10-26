---
title: get_ZoomImage()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a imagem do objeto de zoom. Leia IPPImage.
type: docs
weight: 79
url: /pt/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() método

Obtém a imagem do objeto de zoom. Leia [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Observações

O exemplo demonstra a alteração de uma imagem de um objeto Zoom:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [IZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
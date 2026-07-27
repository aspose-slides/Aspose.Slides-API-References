---
title: set_ZoomImage()
second_title: Referência da API Aspose.Slides para C++
description: Define a imagem para o objeto de zoom. Escreva IPPImage.
type: docs
weight: 92
url: /pt/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) método

Define a imagem para o objeto de zoom. Escreva [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## Observações

O exemplo demonstra a mudança da imagem de um objeto Zoom: 
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
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
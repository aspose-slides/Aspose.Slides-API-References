---
title: get_ZoomImage()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a imagem para o objeto de zoom. Leia IPPImage.
type: docs
weight: 79
url: /pt/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() método

Obtém a imagem do objeto de zoom. Leia [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Observações

O exemplo demonstra a alteração da imagem de um objeto Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
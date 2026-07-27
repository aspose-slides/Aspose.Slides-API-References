---
title: DeletePictureCroppedAreas()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina áreas recortadas del relleno Picture.
type: docs
weight: 430
url: /es/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() method

Eliminar áreas recortadas del relleno [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### Valor de retorno

Imagen recortada o imagen original si no es necesario recortar.

## Observaciones

Este método convierte metarchivos WMF/EMF a una imagen PNG raster mientras recorta.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Elimina áreas recortadas de la imagen PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
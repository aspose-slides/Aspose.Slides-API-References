---
title: DeletePictureCroppedAreas()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina las áreas recortadas del relleno Picture.
type: docs
weight: 430
url: /es/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() método


Elimina las áreas recortadas del relleno [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### Valor de retorno

Imagen recortada o imagen original si no es necesario recortar.
## Observaciones


Este método convierte metarchivos WMF/EMF a imágenes PNG rasterizadas mientras recorta.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Elimina las áreas recortadas de la imagen del PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPPImage](../../ippimage/)
* Clase [PictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
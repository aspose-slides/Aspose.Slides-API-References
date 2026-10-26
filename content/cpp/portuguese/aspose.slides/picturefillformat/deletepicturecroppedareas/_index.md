---
title: DeletePictureCroppedAreas()
second_title: Referência da API Aspose.Slides para C++
description: Exclui áreas recortadas do preenchimento Picture.
type: docs
weight: 430
url: /pt/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() método

Exclui áreas recortadas do preenchimento [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### Valor de retorno

Imagem recortada ou imagem original se o recorte não for necessário.

## Observações

Este método converte arquivos metafile WMF/EMF em imagem PNG raster ao recortar.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Exclui áreas recortadas da imagem PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
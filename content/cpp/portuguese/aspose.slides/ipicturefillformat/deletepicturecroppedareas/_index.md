---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides para C++ Referência da API
description: Excluir áreas recortadas do preenchimento Picture.
type: docs
weight: 430
url: /pt/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() método


Excluir áreas recortadas do preenchimento [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### Valor de Retorno

Imagem recortada ou imagem original se o recorte não for necessário.
## Observações


Este método converte metafiles WMF/EMF em imagens PNG raster enquanto recorta.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Exclui áreas recortadas da imagem PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
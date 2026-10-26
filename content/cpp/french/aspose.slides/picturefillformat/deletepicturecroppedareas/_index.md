---
title: DeletePictureCroppedAreas()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime les zones recadrées du remplissage Picture.
type: docs
weight: 430
url: /fr/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() méthode

Supprimer les zones recadrées du remplissage [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### Valeur de retour

Image recadrée ou image d'origine si le recadrage n'est pas nécessaire.

## Remarques

Cette méthode convertit les métafichiers WMF/EMF en image PNG raster lors du recadrage.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Supprime les zones recadrées de l'image du PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [PictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
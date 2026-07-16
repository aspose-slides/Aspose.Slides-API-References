---
title: CompressImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, elle supprime également les zones recadrées.
type: docs
weight: 443
url: /fr/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) méthode


Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, elle supprime également les zones recadrées.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Si true, la méthode supprimera les zones recadrées de l'image, ce qui pourra réduire davantage sa taille. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | La résolution cible pour la compression, spécifiée comme une valeur de l'énumération [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Valeur de retour

Un **bool** indiquant si l'image a été compressée avec succès. Retourne ****true****

## Remarques

Cette méthode modifie la taille et la résolution de l'image de la même façon que la fonctionnalité "Picture Format -> Compress Pictures" de PowerPoint.

si l'image a été redimensionnée ou recadrée, sinon ****false****

. 


L'exemple suivant montre comment utiliser la méthode **CompressImage** pour réduire la taille d'une image dans une présentation en définissant une résolution cible et en supprimant les zones recadrées : 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Compresse l'image avec une résolution cible de 150 DPI (résolution Web) et supprime les zones recadrées
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) méthode


Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, elle supprime également les zones recadrées.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Si true, la méthode supprimera les zones recadrées de l'image, ce qui pourra réduire davantage sa taille. |
| resolution | **float** | La résolution cible en DPI. Cette valeur doit être positive et définit comment l'image sera redimensionnée. |

### Valeur de retour

Un **bool** indiquant si l'image a été compressée avec succès. Retourne ****true****

## Remarques

Cette méthode modifie la taille et la résolution de l'image de la même façon que la fonctionnalité "Picture Format -> Compress Pictures" de PowerPoint.

si l'image a été redimensionnée ou recadrée, sinon ****false****

. 


L'exemple suivant montre comment utiliser la méthode **CompressImage** pour réduire la taille d'une image dans une présentation en définissant une résolution cible et en supprimant les zones recadrées : 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtient le PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Compresse l'image avec une résolution cible de 150 DPI (résolution Web) et supprime les zones recadrées
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // résolution Web
```

## Voir aussi

* Énum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Classe [PictureFillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
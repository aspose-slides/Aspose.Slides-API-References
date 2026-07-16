---
title: GetImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un objet Thumbnail Image avec un redimensionnement personnalisé.
type: docs
weight: 144
url: /fr/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) méthode

Renvoie un objet Thumbnail Image avec un redimensionnement personnalisé.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | **float** | La valeur par laquelle redimensionner cette Thumbnail dans la direction de l'axe x. |
| scaleY | **float** | La valeur par laquelle redimensionner cette Thumbnail dans la direction de l'axe y. |

### Valeur de retour

[IImage](../../iimage/) objet.
## Remarques

L'exemple suivant montre comment générer des vignettes à partir de PowerPoint [Presentation](../../presentation/) :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
 L'exemple suivant montre comment convertir des diapositives en bitmap et enregistrer les images au format PNG :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Convertit la première diapositive de la présentation en objet Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Enregistre l'image au format PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
 L'exemple suivant montre comment convertir des fichiers PowerPoint PPT/PPTX en JPG :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Crée une image à pleine échelle
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Enregistre l'image sur le disque au format JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
 L'exemple suivant montre comment convertir des fichiers PowerPoint PPT/PPTX en JPG avec des dimensions personnalisées :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Définir les dimensions
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Obtenir les valeurs d'échelle de X et Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Créer une image à pleine échelle
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Enregistrer l'image sur le disque au format JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() méthode

Renvoie un objet Thumbnail Image (20 % de la taille réelle).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) méthode

Renvoie un objet Thumbnail Image avec une taille spécifiée.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Taille de l'image à créer. |

### Valeur de retour

Image object.
## Remarques

L'exemple suivant montre comment convertir des diapositives en images avec des tailles personnalisées en C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Convertit la première diapositive de la présentation en Bitmap avec la taille spécifiée
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Enregistre l'image au format JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) méthode

Renvoie un objet image tiff Thumbnail avec des paramètres spécifiés.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Options Tiff. |

### Valeur de retour

Image object.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) méthode

Renvoie un objet Thumbnail Image.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options de rendu. |

### Valeur de retour

Image object.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) méthode

Renvoie un objet Thumbnail Image avec un redimensionnement personnalisé.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options de rendu. |
| scaleX | **float** | La valeur par laquelle redimensionner cette Thumbnail dans la direction de l'axe x. |
| scaleY | **float** | La valeur par laquelle redimensionner cette Thumbnail dans la direction de l'axe y. |

### Valeur de retour

Bitmap objects.
## Remarques

L'exemple suivant montre comment convertir des diapositives avec des notes et des commentaires en [Images](../../images/) en C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Créer les options de rendu
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Créer les options de mise en page des notes et des commentaires
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Définit la position des notes sur la page
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Définit la position des commentaires sur la page
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Définit la largeur de la zone de sortie des commentaires
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Définit la couleur de la zone des commentaires
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Définir les options de mise en page pour le rendu
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Convertit la première diapositive de la présentation en objet IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Enregistre l'image au format GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) méthode

Renvoie un objet Thumbnail Image avec une taille spécifiée.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options de rendu. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Taille de l'image à créer. |

### Valeur de retour

Image object.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [Slide](../)
* Classe [Size](../../../system.drawing/size/)
* Classe [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
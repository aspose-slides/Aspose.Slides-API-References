---
title: GetImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een Thumbnail Image object met aangepaste schaal.
type: docs
weight: 144
url: /nl/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) methode


Retourneert een Thumbnail Image object met aangepaste schaal.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | **float** | De waarde waarmee deze Thumbnail wordt geschaald in de x-asrichting. |
| scaleY | **float** | De waarde waarmee deze Thumbnail wordt geschaald in de y-asrichting. |

### Retourwaarde

[IImage](../../iimage/) object.
## Opmerkingen



Het volgende voorbeeld laat zien hoe thumbnails te genereren vanuit PowerPoint [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
 Het volgende voorbeeld laat zien hoe dia's te converteren naar een bitmap en de afbeeldingen op te slaan in PNG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converteert de eerste dia in de presentatie naar een Bitmap-object
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Slaat de afbeelding op in PNG-indeling
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
 Het volgende voorbeeld laat zien hoe PowerPoint PPT/PPTX te converteren naar JPG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Maak een afbeelding op volledige schaal
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Sla de afbeelding op schijf in JPEG-indeling
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
 Het volgende voorbeeld laat zien hoe PowerPoint PPT/PPTX te converteren naar JPG met aangepaste afmetingen: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Definieer afmetingen
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Haal geschaalde waarden van X en Y op
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Maak een afbeelding op volledige schaal
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Sla de afbeelding op schijf in JPEG-indeling
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() methode


Retourneert een Thumbnail Image object (20% van de werkelijke grootte).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) methode


Retourneert een Thumbnail Image object met opgegeven grootte.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de te maken afbeelding. |

### Retourwaarde

Image object.
## Opmerkingen



Het volgende voorbeeld laat zien hoe dia's te converteren naar afbeeldingen met aangepaste afmetingen met behulp van C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converteert de eerste dia in de presentatie naar een Bitmap met de opgegeven grootte
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Slaat de afbeelding op in JPEG-indeling
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) methode


Retourneert een Thumbnail tiff image object met opgegeven parameters.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff-opties. |

### Retourwaarde

Image object.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) methode


Retourneert een Thumbnail Image object.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |

### Retourwaarde

Image object.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) methode


Retourneert een Thumbnail Image object met aangepaste schaal.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| scaleX | **float** | De waarde waarmee deze Thumbnail wordt geschaald in de x-asrichting. |
| scaleY | **float** | De waarde waarmee deze Thumbnail wordt geschaald in de y-asrichting. |

### Retourwaarde

Bitmapobjecten.
## Opmerkingen



Het volgende voorbeeld laat zien hoe dia's met notities en opmerkingen te converteren naar [Images](../../images/) met behulp van C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Maak de renderopties
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Maak notities- en opmerkingenlayoutopties
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Stelt de positie van de notities op de pagina in
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Stelt de positie van de opmerkingen op de pagina in
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Stelt de breedte van het opmerkingengebied in
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Stelt de kleur voor het opmerkingengebied in
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Stel layoutopties in voor het renderen
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Converteert de eerste dia van de presentatie naar een IImage-object
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Slaat de afbeelding op in GIF-indeling
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) methode


Retourneert een Thumbnail Image object met opgegeven grootte.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderopties. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Grootte van de te maken afbeelding. |

### Retourwaarde

Image object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
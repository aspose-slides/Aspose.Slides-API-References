---
title: GetImage()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett Thumbnail Image-objekt med anpassad skalning.
type: docs
weight: 144
url: /sv/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) metod


Returnerar ett Thumbnail Image-objekt med anpassad skalning.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | **float** | Värdet som används för att skala denna Thumbnail i x-axelns riktning. |
| scaleY | **float** | Värdet som används för att skala denna Thumbnail i y-axelns riktning. |

### Returvärde

[IImage](../../iimage/) objekt.
## Anmärkningar



Följande exempel visar hur man genererar miniatyrbilder från PowerPoint [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Följande exempel visar hur man konverterar bildspel till bitmap och sparar bilderna i PNG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Konverterar den första bilden i presentationen till ett Bitmap-objekt
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Sparar bilden i PNG-format
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Följande exempel visar hur man konverterar PowerPoint PPT/PPTX till JPG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Skapa en fullskalig bild
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Spara bilden till disk i JPEG-format
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Följande exempel visar hur man konverterar PowerPoint PPT/PPTX till JPG med anpassade dimensioner: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Definiera dimensioner
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Hämta skalade värden för X och Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Skapa en fullskalig bild
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Spara bilden till disk i JPEG-format
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() metod


Returnerar ett Thumbnail Image-objekt (20 % av verklig storlek).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) metod


Returnerar ett Thumbnail Image-objekt med angiven storlek.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på bilden som ska skapas. |

### Returvärde

Image-objekt.
## Anmärkningar



Följande exempel visar hur man konverterar bildspel till bilder med anpassade storlekar med C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Konverterar den första bilden i presentationen till en Bitmap med den angivna storleken
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Sparar bilden i JPEG-format
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metod


Returnerar ett Thumbnail tiff-bildobjekt med angivna parametrar.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff-alternativ. |

### Returvärde

Image-objekt.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metod


Returnerar ett Thumbnail Image-objekt.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |

### Returvärde

Image-objekt.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metod


Returnerar ett Thumbnail Image-objekt med anpassad skalning.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| scaleX | **float** | Värdet som används för att skala denna Thumbnail i x-axelns riktning. |
| scaleY | **float** | Värdet som används för att skala denna Thumbnail i y-axelns riktning. |

### Returvärde

Bitmap-objekt.
## Anmärkningar



Följande exempel visar hur man konverterar bildspel med anteckningar och kommentarer till [Images](../../images/) med C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Skapa renderingsalternativ
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Skapa layoutalternativ för anteckningar och kommentarer
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Ställer in positionen för anteckningarna på sidan
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Ställer in positionen för kommentarerna på sidan
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Ställer in bredden på kommentarsutmatningsområdet
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Ställer in färgen för kommentarsområdet
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Ställ in layoutalternativ för rendering
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Konverterar den första bilden i presentationen till ett IImage-objekt
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Sparar bilden i GIF-format
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metod


Returnerar ett Thumbnail Image-objekt med angiven storlek.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativ. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på bilden som ska skapas. |

### Returvärde

Image-objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImage](../../iimage/)
* Klass [Slide](../)
* Klass [Size](../../../system.drawing/size/)
* Klass [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Klass [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namnområde [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
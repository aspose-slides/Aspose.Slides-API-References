---
title: GetImage()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem.
type: docs
weight: 144
url: /pl/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) metoda


Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| scaleX | **float** | Wartość, o którą należy skalować tę miniaturę wzdłuż osi x. |
| scaleY | **float** | Wartość, o którą należy skalować tę miniaturę wzdłuż osi y. |

### Wartość zwracana

[IImage](../../iimage/) obiekt.

## Uwagi



Poniższy przykład pokazuje, jak generować miniatury z PowerPoint [Presentation](../../presentation/):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Poniższy przykład pokazuje, jak konwertować slajdy na bitmapy i zapisywać obrazy w formacie PNG:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converts the first slide in the presentation to a Bitmap object
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Saves the image in the PNG format
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Poniższy przykład pokazuje, jak konwertować PowerPoint PPT/PPTX na JPG:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Utwórz obraz w pełnym rozmiarze
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Zapisz obraz na dysku w formacie JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Poniższy przykład pokazuje, jak konwertować PowerPoint PPT/PPTX na JPG przy użyciu niestandardowych wymiarów:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Zdefiniuj wymiary
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Pobierz skalowane wartości X i Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Utwórz obraz w pełnym rozmiarze
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Zapisz obraz na dysku w formacie JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() metoda


Zwraca obiekt Thumbnail Image (20% rzeczywistego rozmiaru).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) metoda


Zwraca obiekt Thumbnail Image o określonym rozmiarze.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekt Image.

## Uwagi



Poniższy przykład pokazuje, jak konwertować slajdy na obrazy o niestandardowych rozmiarach przy użyciu C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Konwertuje pierwszy slajd w prezentacji na Bitmapę o określonym rozmiarze
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Zapisuje obraz w formacie JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metoda


Zwraca obiekt Thumbnail tiff image z określonymi parametrami.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opcje tiff. |

### Wartość zwracana

Obiekt Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metoda


Zwraca obiekt Thumbnail Image.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |

### Wartość zwracana

Obiekt Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda


Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| scaleX | **float** | Wartość, o którą należy skalować tę miniaturę wzdłuż osi x. |
| scaleY | **float** | Wartość, o którą należy skalować tę miniaturę wzdłuż osi y. |

### Wartość zwracana

Obiekty Bitmap.

## Uwagi



Poniższy przykład pokazuje, jak konwertować slajdy z notatkami i komentarzami na [Images](../../images/) przy użyciu C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Create the rendering options
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Create notes and comments layouting options
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Sets the position of the notes on the page
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Sets the position of the comments on the page
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Sets the width of the comment output area
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Sets the color for the comments area
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Set layout options for rendering
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Converts the first slide of the presentation to a IImage object
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Saves the image in the GIF format
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda


Zwraca obiekt Thumbnail Image o określonym rozmiarze.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekt Image.

## Zobacz również

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IImage](../../iimage/)
* Klasa [Slide](../)
* Klasa [Size](../../../system.drawing/size/)
* Klasa [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Klasa [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
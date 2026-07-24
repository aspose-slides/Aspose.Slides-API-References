---
title: GetImage()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück.
type: docs
weight: 144
url: /de/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) Methode


Gibt ein Thumbnail Image-Objekt mit benutzerdefinierter Skalierung zurück.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | **float** | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scaleY | **float** | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

### Rückgabewert

[IImage](../../iimage/) Objekt.
## Anmerkungen



Das folgende Beispiel zeigt, wie Thumbnails aus PowerPoint [Presentation](../../presentation/) erzeugt werden: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Das folgende Beispiel zeigt, wie Folien in Bitmaps konvertiert und die Bilder im PNG-Format gespeichert werden: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Konvertiert die erste Folie in der Präsentation in ein Bitmap-Objekt
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Speichert das Bild im PNG-Format
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Das folgende Beispiel zeigt, wie PowerPoint-PPT/PPTX in JPG konvertiert wird: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Erstelle ein Bild in voller Größe
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Speichere das Bild auf der Festplatte im JPEG-Format
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Das folgende Beispiel zeigt, wie PowerPoint-PPT/PPTX mit benutzerdefinierten Abmessungen in JPG konvertiert wird: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Dimensionen definieren
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Skalierte Werte für X und Y ermitteln
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Erstelle ein Bild in voller Größe
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Speichere das Bild auf der Festplatte im JPEG-Format
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() Methode


Gibt ein Thumbnail Image-Objekt (20 % der Originalgröße) zurück.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) Methode


Gibt ein Thumbnail Image-Objekt mit der angegebenen Größe zurück.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Größe des zu erstellenden Bildes. |

### Rückgabewert

Image-Objekt.
## Anmerkungen



Das folgende Beispiel zeigt, wie Folien mit benutzerdefinierten Größen in Bilder konvertiert werden, wobei C# verwendet wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Konvertiert die erste Folie in der Präsentation in ein Bitmap mit der angegebenen Größe
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Speichert das Bild im JPEG-Format
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) Methode


Gibt ein Thumbnail-tiff-Bildobjekt mit den angegebenen Parametern zurück.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff-Optionen. |

### Rückgabewert

Image-Objekt.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) Methode


Gibt ein Thumbnail Image-Objekt zurück.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-Optionen. |

### Rückgabewert

Image-Objekt.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) Methode


Gibt ein Thumbnail Image-Objekt mit benutzerdefinierter Skalierung zurück.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-Optionen. |
| scaleX | **float** | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scaleY | **float** | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

### Rückgabewert

Bitmap-Objekte.
## Anmerkungen



Das folgende Beispiel zeigt, wie Folien mit Notizen und Kommentaren in [Images](../../images/) konvertiert werden, wobei C# verwendet wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Rendering-Optionen erstellen
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Notizen- und Kommentare-Layoutoptionen erstellen
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Setzt die Position der Notizen auf der Seite
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Setzt die Position der Kommentare auf der Seite
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Setzt die Breite des Kommentarbereichs
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Setzt die Farbe für den Kommentarbereich
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Setzt Layoutoptionen für das Rendering
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Konvertiert die erste Folie der Präsentation in ein IImage-Objekt
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Speichert das Bild im GIF-Format
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) Methode


Gibt ein Thumbnail Image-Objekt mit der angegebenen Größe zurück.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering-Optionen. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Größe des zu erstellenden Bildes. |

### Rückgabewert

Image-Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [Slide](../)
* Klasse [Size](../../../system.drawing/size/)
* Klasse [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Klasse [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
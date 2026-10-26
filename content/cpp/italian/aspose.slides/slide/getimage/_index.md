---
title: GetImage()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un oggetto Thumbnail Image con scala personalizzata.
type: docs
weight: 144
url: /it/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) metodo

Restituisce un oggetto Thumbnail Image con scala personalizzata.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | **float** | Il valore con cui scalare questo Thumbnail nella direzione dell'asse x. |
| scaleY | **float** | Il valore con cui scalare questo Thumbnail nella direzione dell'asse y. |

### Valore restituito

[IImage](../../iimage/) object.

## Osservazioni

Il seguente esempio mostra come generare le miniature da PowerPoint [Presentation](../../presentation/):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Il seguente esempio mostra come convertire le diapositive in bitmap e salvare le immagini in PNG:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converte la prima diapositiva nella presentazione in un oggetto Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Salva l'immagine nel formato PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Il seguente esempio mostra come convertire PowerPoint PPT/PPTX in JPG:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Crea un'immagine a piena scala
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Salva l'immagine su disco in formato JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Il seguente esempio mostra come convertire PowerPoint PPT/PPTX in JPG con dimensioni personalizzate:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Definisci le dimensioni
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Ottieni i valori scalati di X e Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Crea un'immagine a piena scala
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Salva l'immagine su disco in formato JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() metodo

Restituisce un oggetto Thumbnail Image (20% della dimensione reale).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) metodo

Restituisce un oggetto Thumbnail Image con dimensione specificata.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Dimensione dell'immagine da creare. |

### Valore restituito

Image object.

## Osservazioni

Il seguente esempio mostra come convertire le diapositive in immagini con dimensioni personalizzate utilizzando C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converte la prima diapositiva nella presentazione in un Bitmap con le dimensioni specificate
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Salva l'immagine nel formato JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metodo

Restituisce un oggetto immagine tiff Thumbnail con parametri specificati.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opzioni tiff. |

### Valore restituito

Image object.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metodo

Restituisce un oggetto Thumbnail Image.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni di rendering. |

### Valore restituito

Image object.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metodo

Restituisce un oggetto Thumbnail Image con scala personalizzata.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni di rendering. |
| scaleX | **float** | Il valore con cui scalare questo Thumbnail nella direzione dell'asse x. |
| scaleY | **float** | Il valore con cui scalare questo Thumbnail nella direzione dell'asse y. |

### Valore restituito

Oggetti Bitmap.

## Osservazioni

Il seguente esempio mostra come convertire le diapositive con note e commenti in [Images](../../images/) utilizzando C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Crea le opzioni di rendering
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Crea le opzioni di layout per note e commenti
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Imposta la posizione delle note sulla pagina
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Imposta la posizione dei commenti sulla pagina
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Imposta la larghezza dell'area dei commenti
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Imposta il colore dell'area dei commenti
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Imposta le opzioni di layout per il rendering
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Converte la prima diapositiva della presentazione in un oggetto IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Salva l'immagine nel formato GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metodo

Restituisce un oggetto Thumbnail Image con dimensione specificata.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opzioni di rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Dimensione dell'immagine da creare. |

### Valore restituito

Image object.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
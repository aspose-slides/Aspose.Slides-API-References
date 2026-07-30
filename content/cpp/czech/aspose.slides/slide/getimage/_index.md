---
title: GetImage()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací objekt Thumbnail Image s vlastním škálováním.
type: docs
weight: 144
url: /cs/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) metoda


Vrací objekt Thumbnail Image s vlastním škálováním.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| scaleX | **float** | Hodnota, o kterou se má tento Thumbnail v ose x změnit velikost. |
| scaleY | **float** | Hodnota, o kterou se má tento Thumbnail v ose y změnit velikost. |

### Návratová hodnota

[IImage](../../iimage/) objekt.

## Poznámky



Následující příklad ukazuje, jak generovat náhledy z PowerPointu [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Následující příklad ukazuje, jak převádět snímky na bitmapu a ukládat obrázky ve formátu PNG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Převádí první snímek v prezentaci na objekt Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Ukládá obrázek ve formátu PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Následující příklad ukazuje, jak převést PowerPoint PPT/PPTX na JPG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Vytvoří obrázek v plném měřítku
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Uloží obrázek na disk ve formátu JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Následující příklad ukazuje, jak převést PowerPoint PPT/PPTX na JPG s vlastním rozměrem: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Definujte rozměry
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Získejte škálované hodnoty X a Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Vytvořte obrázek v plném měřítku
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Uložte obrázek na disk ve formátu JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() metoda


Vrací objekt Thumbnail Image (20 % skutečné velikosti).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) metoda


Vrací objekt Thumbnail Image s určenou velikostí.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost obrázku, který má být vytvořen. |

### Návratová hodnota

Objekt Image.

## Poznámky



Následující příklad ukazuje, jak převádět snímky na obrázky s vlastními velikostmi pomocí C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Převede první snímek v prezentaci na Bitmapu se zadanou velikostí
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Uloží obrázek ve formátu JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metoda


Vrací objekt náhledového TIFF obrázku s určenými parametry.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Možnosti TIFF. |

### Návratová hodnota

Objekt Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metoda


Vrací objekt Thumbnail Image.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |

### Návratová hodnota

Objekt Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metoda


Vrací objekt Thumbnail Image s vlastním škálováním.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| scaleX | **float** | Hodnota, o kterou se má tento Thumbnail v ose x změnit velikost. |
| scaleY | **float** | Hodnota, o kterou se má tento Thumbnail v ose y změnit velikost. |

### Návratová hodnota

Objekty Bitmap.

## Poznámky



Následující příklad ukazuje, jak převádět snímky s poznámkami a komentáři do [Images](../../images/) pomocí C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Vytvořte možnosti vykreslování
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Vytvořte možnosti rozvržení poznámek a komentářů
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Nastaví pozici poznámek na stránce
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Nastaví pozici komentářů na stránce
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Nastaví šířku oblasti výstupu komentářů
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Nastaví barvu oblasti komentářů
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Nastavte možnosti rozvržení pro vykreslování
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Převádí první snímek prezentace na objekt IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Uloží obrázek ve formátu GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metoda


Vrací objekt Thumbnail Image s určenou velikostí.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost obrázku, který má být vytvořen. |

### Návratová hodnota

Objekt Image.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImage](../../iimage/)
* Třída [Slide](../)
* Třída [Size](../../../system.drawing/size/)
* Třída [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Třída [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
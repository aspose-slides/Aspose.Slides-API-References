---
title: GetImage()
second_title: Aspose.Slides C++ API-referencia
description: Visszaad egy előnézeti kép objektumot egyéni méretezéssel.
type: docs
weight: 144
url: /hu/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) metódus


Visszaad egy Thumbnail Image objektumot egyéni méretezéssel.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Visszatérési érték

[IImage](../../iimage/) objektum.

## Megjegyzések



Az alábbi példa bemutatja, hogyan lehet előnézeti képeket létrehozni a PowerPointból [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
Az alábbi példa bemutatja, hogyan lehet diákot bitmap formátumba konvertálni és a képeket PNG-ben menteni: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Átalakítja a bemutató első diaját egy Bitmap objektummá
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Elmenti a képet PNG formátumban
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
Az alábbi példa bemutatja, hogyan lehet a PowerPoint PPT/PPTX fájlokat JPG-be konvertálni: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Létrehoz egy teljes méretű képet
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Elmenti a képet lemezre JPEG formátumban
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
Az alábbi példa bemutatja, hogyan lehet a PowerPoint PPT/PPTX fájlokat JPG-be egyedi méretekkel konvertálni: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Határozza meg a méreteket
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Az X és Y méretezett értékeinek lekérése
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Létrehoz egy teljes méretű képet
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Mentse a képet lemezre JPEG formátumban
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() metódus


Visszaad egy Thumbnail Image objektumot (a valós méret 20%-a).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) metódus


Visszaad egy Thumbnail Image objektumot a megadott mérettel.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | A létrehozandó kép mérete. |

### Visszatérési érték

Image objektum.

## Megjegyzések



Az alábbi példa bemutatja, hogyan lehet diákot saját méretekkel képekké konvertálni C# használatával. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Átalakítja a bemutató első diaját egy megadott méretű Bitmap objektummá
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Elmenti a képet JPEG formátumban
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metódus


Visszaad egy Thumbnail tiff kép objektumot a megadott paraméterekkel.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff beállítások. |

### Visszatérési érték

Image objektum.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metódus


Visszaad egy Thumbnail Image objektumot.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderelési beállítások. |

### Visszatérési érték

Image objektum.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metódus


Visszaad egy Thumbnail Image objektumot egyéni méretezéssel.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderelési beállítások. |
| scaleX | **float** | Az a érték, amellyel a Thumbnail-t az x tengely irányában méretezi. |
| scaleY | **float** | Az a érték, amellyel a Thumbnail-t a y tengely irányában méretezi. |

### Visszatérési érték

Bitmap objektumok.
## Megjegyzések



Az alábbi példa bemutatja, hogyan lehet a diákot jegyzetekkel és megjegyzésekkel [Images](../../images/)-re konvertálni C# használatával. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Hozza létre a renderelési beállításokat
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Létrehozza a jegyzetek és megjegyzések elrendezési beállításait
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Beállítja a jegyzetek pozícióját az oldalon
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Beállítja a megjegyzések pozícióját az oldalon
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Beállítja a megjegyzés kimeneti terület szélességét
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Beállítja a megjegyzések terület színét
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Beállítja az elrendezési opciókat a rendereléshez
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Átalakítja a bemutató első diaját IImage objektummá
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Elmenti a képet GIF formátumban
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metódus


Visszaad egy Thumbnail Image objektumot a megadott mérettel.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderelési beállítások. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | A létrehozandó kép mérete. |

### Visszatérési érték

Image objektum.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
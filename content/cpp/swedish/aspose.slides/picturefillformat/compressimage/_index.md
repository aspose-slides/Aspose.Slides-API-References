---
title: CompressImage()
second_title: Aspose.Slides för C++ API-referens
description: Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden.
type: docs
weight: 443
url: /sv/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) metod


Komprimerar bilden genom att minska dess storlek baserat på formens storlek och den angivna upplösningen. Eventuellt tar den också bort beskurna områden.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Om true, kommer metoden att ta bort de beskurna områdena i bilden, vilket potentiellt minskar dess storlek ytterligare. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Måluppslösningen för komprimeringen, specificerad som ett värde i [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/)-enumet. |

### Returvärde

En **bool** som indikerar om bilden komprimerades framgångsrikt. Returnerar ****true****

## Anmärkningar


Denna metod ändrar bildens storlek och upplösning på samma sätt som PowerPoints funktion "Picture Format -> Compress Pictures".

om bilden har ändrats i storlek eller beskärts, annars ****false****


Följande exempel demonstrerar hur man använder **CompressImage**-metoden för att minska en bilds storlek i en presentation genom att ange en måluppslösning och ta bort beskurna områden: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Komprimera bilden med en målupplösning på 150 DPI (webbupplösning) och ta bort beskurna områden
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) metod


Komprimerar bilden genom att minska dess storlek baserat på formens storlek och den angivna upplösningen. Eventuellt tar den också bort beskurna områden.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Om true, kommer metoden att ta bort de beskurna områdena i bilden, vilket potentiellt minskar dess storlek ytterligare. |
| resolution | **float** | Måluppslösning i DPI. Detta värde måste vara positivt och definierar hur bilden kommer att skalas om. |

### Returvärde

En **bool** som indikerar om bilden komprimerades framgångsrikt. Returnerar ****true****

## Anmärkningar


Denna metod ändrar bildens storlek och upplösning på samma sätt som PowerPoints funktion "Picture Format -> Compress Pictures".

om bilden har ändrats i storlek eller beskärts, annars ****false****


Följande exempel demonstrerar hur man använder **CompressImage**-metoden för att minska en bilds storlek i en presentation genom att ange en måluppslösning och ta bort beskurna områden: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Komprimera bilden med en målupplösning på 150 DPI (webbupplösning) och ta bort beskurna områden
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Webbupplösning
```

## Se även

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Klass [PictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
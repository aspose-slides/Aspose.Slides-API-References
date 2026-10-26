---
title: CompressImage()
second_title: Aspose.Slides för C++ API-referens
description: Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden.
type: docs
weight: 443
url: /sv/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) metod

Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Om true, kommer metoden att ta bort de beskurna områdena i bilden, vilket eventuellt ytterligare minskar dess storlek. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Måluppslösningen för komprimering, specificerad som ett värde av enumen [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Returvärde

En **bool** som indikerar om bilden komprimerades framgångsrikt. Returnerar ****true****

## Anmärkningar

Denna metod ändrar bildens storlek och upplösning på liknande sätt som PowerPoints "Picture Format -> Compress Pictures"-funktion.

om bilden har ändrat storlek eller beskärts, annars ****false****

. 

Följande exempel visar hur man använder **CompressImage**-metoden för att minska storleken på en bild i en presentation genom att ange en måluppslösning och ta bort beskurna områden: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Komprimera bilden med en målupplösning på 150 DPI (webbupplösning) och ta bort beskurna områden
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) metod

Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Om true, kommer metoden att ta bort de beskurna områdena i bilden, vilket eventuellt ytterligare minskar dess storlek. |
| resolution | **float** | Måluppslösningen i DPI. Detta värde måste vara positivt och definierar hur bilden kommer att skalas. |

### Returvärde

En **bool** som indikerar om bilden komprimerades framgångsrikt. Returnerar ****true****

## Anmärkningar

Denna metod ändrar bildens storlek och upplösning på liknande sätt som PowerPoints "Picture Format -> Compress Pictures"-funktion.

om bilden har ändrat storlek eller beskärts, annars ****false****

. 

Följande exempel visar hur man använder **CompressImage**-metoden för att minska storleken på en bild i en presentation genom att ange en måluppslösning och ta bort beskurna områden: 
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
* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
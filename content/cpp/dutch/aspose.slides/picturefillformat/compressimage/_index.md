---
title: CompressImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden.
type: docs
weight: 443
url: /nl/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) methode


Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Indien waar, zal de methode de bijgesneden gebieden van de afbeelding verwijderen, waardoor de grootte mogelijk verder wordt verkleind. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | De doelresolutie voor compressie, opgegeven als een waarde van de [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) enum. |

### Retourwaarde

Een **bool** die aangeeft of de afbeelding succesvol is gecomprimeerd. Retourneert ****true****

## Opmerkingen


Deze methode wijzigt de grootte en resolutie van de afbeelding, vergelijkbaar met de functie "Picture Format -> Compress Pictures" van PowerPoint.


indien de afbeelding is verkleind of bijgesneden, anders ****false****

. 


Het volgende voorbeeld toont hoe de **CompressImage** methode te gebruiken om de grootte van een afbeelding in een presentatie te verkleinen door een doelresolutie in te stellen en bijgesneden gebieden te verwijderen: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Comprimeer de afbeelding met een doelresolutie van 150 DPI (webresolutie) en verwijder bijgesneden gebieden
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) methode


Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Indien waar, zal de methode de bijgesneden gebieden van de afbeelding verwijderen, waardoor de grootte mogelijk verder wordt verkleind. |
| resolution | **float** | De doelresolutie in DPI. Deze waarde moet positief zijn en bepaalt hoe de afbeelding wordt geschaald. |

### Retourwaarde

Een **bool** die aangeeft of de afbeelding succesvol is gecomprimeerd. Retourneert ****true****

## Opmerkingen


Deze methode wijzigt de grootte en resolutie van de afbeelding, vergelijkbaar met de functie "Picture Format -> Compress Pictures" van PowerPoint.


indien de afbeelding is verkleind of bijgesneden, anders ****false****

. 


Het volgende voorbeeld toont hoe de **CompressImage** methode te gebruiken om de grootte van een afbeelding in een presentatie te verkleinen door een doelresolutie in te stellen en bijgesneden gebieden te verwijderen: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Haalt de PictureFrame op
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Comprimeer de afbeelding met een doelresolutie van 150 DPI (webresolutie) en verwijder bijgesneden gebieden
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Webresolutie
```

## Zie ook

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Klasse [PictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
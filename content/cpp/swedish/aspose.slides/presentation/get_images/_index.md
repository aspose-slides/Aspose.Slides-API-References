---
title: get_Images()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar samlingen av alla bilder i presentationen. Skrivskyddad IImageCollection.
type: docs
weight: 209
url: /sv/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() metod

Returnerar samlingen av alla bilder i presentationen. Skrivskyddad [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Anmärkningar

Följande exempel visar hur man lägger till en bild som BLOB i PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// skapar en ny presentation som bilden kommer att läggas till.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Låt oss lägga till bilden i presentationen - vi väljer KeepLocked-beteende eftersom vi
// INTE avser att komma åt filen "largeImage.png".
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Sparar presentationen. Medan en stor presentation skrivs ut, förblir minnesanvändningen
// förblir låg genom presentationens livscykel
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 Följande exempel lägger till en hyperlänk till en bild i en PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Lägger till bild i presentationen
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Skapar bildruta på bild 1 baserat på tidigare tillagd bild
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImageCollection](../../iimagecollection/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
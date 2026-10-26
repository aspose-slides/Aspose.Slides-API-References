---
title: get_Images()
second_title: Aspose.Slides for C++ API-referentie
description: Retourneert de collectie van alle afbeeldingen in de presentatie. Alleen-lezen IImageCollection.
type: docs
weight: 209
url: /nl/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() methode


Retourneert de verzameling van alle afbeeldingen in de presentatie. Alleen-lezen [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Opmerkingen


De volgende voorbeelden laten zien hoe je een afbeelding als BLOB toevoegt in PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// maakt een nieuwe presentatie waarin de afbeelding zal worden toegevoegd.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Laten we de afbeelding aan de presentatie toevoegen - we kiezen KeepLocked gedrag omdat we
// NIET van plan om het "largeImage.png" bestand te benaderen.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Slaat de presentatie op. Terwijl een grote presentatie wordt uitgegeven, blijft het geheugenverbruik
// laag gedurende de levensduur van het pres object's lifecycle
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 De volgende voorbeelden voegen een hyperlink toe aan een afbeelding in een PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Voegt afbeelding toe aan presentatie
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Maakt een afbeeldingframe op dia 1 op basis van eerder toegevoegde afbeelding
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImageCollection](../../iimagecollection/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
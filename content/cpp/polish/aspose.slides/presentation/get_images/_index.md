---
title: get_Images()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca kolekcję wszystkich obrazów w prezentacji. Tylko do odczytu IImageCollection.
type: docs
weight: 209
url: /pl/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() metoda

Zwraca kolekcję wszystkich obrazów w prezentacji. Tylko do odczytu [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Uwagi

Poniższe przykłady pokazują, jak dodać obraz jako BLOB w programie PowerPoint [Presentation](../).
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// tworzy nową prezentację, do której zostanie dodany obraz.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Dodajmy obraz do prezentacji - wybieramy zachowanie KeepLocked, ponieważ nie
// NIE zamierzamy uzyskać dostępu do pliku "largeImage.png".
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Zapisuje prezentację. Podczas gdy duża prezentacja jest generowana, zużycie pamięci
// pozostaje niskie przez cały cykl życia obiektu pres.
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 Poniższe przykłady dodają hiperlink do obrazu w programie PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Dodaje obraz do prezentacji
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Tworzy ramkę obrazu na slajdzie 1 na podstawie wcześniej dodanego obrazu
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zobacz też

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IImageCollection](../../iimagecollection/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
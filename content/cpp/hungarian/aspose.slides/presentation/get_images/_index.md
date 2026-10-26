---
title: get_Images()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a prezentációban található összes kép gyűjteményét. Csak olvasható IImageCollection.
type: docs
weight: 209
url: /hu/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() metódus

Visszaadja a prezentációban található összes kép gyűjteményét. Csak olvasható [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Megjegyzések

A következő példák bemutatják, hogyan lehet képet BLOB-ként hozzáadni a PowerPoint [Presentation](../)-ban.  
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// új prezentációt hoz létre, amelyhez a képet hozzáadjuk.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Adjunk hozzá egy képet a prezentációhoz – a KeepLocked viselkedést választjuk, mert
// NEM szándékozunk hozzáférni a "largeImage.png" fájlhoz.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Mentse a prezentációt. Míg egy nagy prezentáció kerül kiírásra, a memóriahasználat
// alacsony marad a pres objektum élettartama során
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```  
A következő példák hiperhivatkozást adnak egy képre a PowerPoint [Presentation](../)-ban.  
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Képet ad hozzá a prezentációhoz
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Létrehoz egy képkockát az 1. dián a korábban hozzáadott kép alapján
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IImageCollection](../../iimagecollection/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
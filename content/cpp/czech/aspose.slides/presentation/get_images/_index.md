---
title: get_Images()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací kolekci všech obrázků v prezentaci. Pouze pro čtení IImageCollection.
type: docs
weight: 209
url: /cs/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() metoda

Vrací kolekci všech obrázků v prezentaci. Pouze pro čtení [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Poznámky

Následující příklady ukazují, jak přidat obrázek jako BLOB v PowerPointu [Presentation](../).
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// vytvoří novou prezentaci, do které bude obrázek přidán.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Přidáme obrázek do prezentace – zvolíme chování KeepLocked, protože
// NEPLÁNUJEME přistupovat k souboru "largeImage.png" file.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Ukládá prezentaci. Zatímco je vytvářena velká prezentace, spotřeba paměti
// zůstává nízká během životního cyklu objektu pres
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 Následující příklady přidávají hypertextový odkaz k obrázku v PowerPointu [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Přidá obrázek do prezentace
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Vytvoří rámeček obrázku na snímku 1 na základě dříve přidaného obrázku
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImageCollection](../../iimagecollection/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
---
title: get_Images()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur lesend IImageCollection.
type: docs
weight: 209
url: /de/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() Methode


Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur lesend [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Bemerkungen


Das folgende Beispiel zeigt, wie ein Bild als BLOB in PowerPoint [Presentation](../) hinzugefügt wird. 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// erstellt eine neue Präsentation, zu der das Bild hinzugefügt wird.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Fügen wir das Bild zur Präsentation hinzu – wir wählen das KeepLocked-Verhalten, weil wir
// NICHT beabsichtigen, auf die Datei "largeImage.png" zuzugreifen.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Speichert die Präsentation. Während eine große Präsentation ausgegeben wird, bleibt der Speicherverbrauch
// niedrig während des gesamten Lebenszyklus des pres-Objekts.
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 Die folgenden Beispiele fügen einem Bild in einer PowerPoint [Presentation](../) einen Hyperlink hinzu. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Fügt Bild zur Präsentation hinzu
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Erstellt Bildrahmen auf Folie 1 basierend auf dem zuvor hinzugefügten Bild
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImageCollection](../../iimagecollection/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)
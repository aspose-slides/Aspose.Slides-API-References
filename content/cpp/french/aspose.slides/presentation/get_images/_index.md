---
title: get_Images()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la collection de toutes les images de la présentation. Lecture seule IImageCollection.
type: docs
weight: 209
url: /fr/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() méthode


Renvoie la collection de toutes les images dans la présentation. Lecture seule [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Remarques


Les exemples suivants montrent comment ajouter une image en tant que BLOB dans PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// crée une nouvelle présentation à laquelle l'image sera ajoutée.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Ajoutons l'image à la présentation - nous choisissons le comportement KeepLocked parce que nous
// n'avons PAS l'intention d'accéder au fichier \"largeImage.png\".
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Enregistre la présentation. Bien qu'une grande présentation soit générée, la consommation de mémoire
// reste faible tout au long du cycle de vie de l'objet pres.
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 Les exemples suivants ajoutent un hyperlien à une image dans un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Adds image to presentation
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Creates picture frame on slide 1 based on previously added image
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImageCollection](../../iimagecollection/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
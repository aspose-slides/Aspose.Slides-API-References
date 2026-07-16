---
title: WriteAsEmf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Enregistre l'image SVG au format EMF.
type: docs
weight: 53
url: /fr/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) méthode

Enregistre l'image SVG au format EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux cible |

## Remarques

L'exemple suivant montre comment enregistrer l'image SVG dans un métafichier. 
```cpp
// Crée la nouvelle image SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Enregistre l'image SVG en tant que métafichier
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
Cet exemple montre comment ajouter l'image SVG en tant que métafichier à la collection d'images de la présentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Crée la nouvelle image SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Enregistre l'image SVG en tant que métafichier
svgImage->WriteAsEmf(memStream);
// Ajoute le métafichier à la collection d'images
pres->get_Images()->AddImage(memStream->ToArray());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [ISvgImage](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
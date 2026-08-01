---
title: WriteAsEmf()
second_title: Aspose.Slides voor C++ API-referentie
description: Slaat de SVG-afbeelding op als een EMF-bestand.
type: docs
weight: 53
url: /nl/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) methode


Slaat de SVG-afbeelding op als een EMF-bestand.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Doelstream |
## Opmerkingen



Het volgende voorbeeld toont hoe de SVG-afbeelding kan worden opgeslagen in een metafile. 
```cpp
// Maakt de nieuwe SVG-afbeelding
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Slaat de SVG-afbeelding op als een metafile
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Deze voorbeeld laat zien hoe de SVG-afbeelding als metafile kan worden toegevoegd aan de afbeeldingscollectie van de presentatie. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Maakt de nieuwe SVG-afbeelding
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Slaat de SVG-afbeelding op als een metafile
svgImage->WriteAsEmf(memStream);
// Voegt de metafile toe aan de afbeeldingscollectie
pres->get_Images()->AddImage(memStream->ToArray());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
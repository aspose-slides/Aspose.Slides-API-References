---
title: WriteAsEmf()
second_title: Aspose.Slides voor C++ API-referentie
description: Slaat de SVG-afbeelding op als een EMF-bestand.
type: docs
weight: 66
url: /nl/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) methode


Slaat de SVG-afbeelding op als een EMF-bestand.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Doelstream |
## Opmerkingen



Het volgende voorbeeld toont hoe u de SVG-afbeelding opslaat in een metafile. 
```cpp
// Maakt de nieuwe SVG-afbeelding
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Slaat de SVG-afbeelding op als een metabestand
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Dit voorbeeld laat zien hoe u de SVG-afbeelding als metafile toevoegt aan de afbeeldingsverzameling van de presentatie. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Maakt de nieuwe SVG-afbeelding
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Slaat de SVG-afbeelding op als een metabestand
svgImage->WriteAsEmf(memStream);
// Voegt metabestand toe aan de afbeeldingsverzameling
pres->get_Images()->AddImage(memStream->ToArray());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SvgImage](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
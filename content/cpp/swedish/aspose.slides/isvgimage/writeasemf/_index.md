---
title: WriteAsEmf()
second_title: Aspose.Slides för C++ API-referens
description: Sparar SVG-bilden som en EMF-fil.
type: docs
weight: 53
url: /sv/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metod


Sparar SVG-bilden som en EMF-fil.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Måldataström |
## Anmärkningar



Följande exempel visar hur man sparar SVG-bilden i en metafil. 
```cpp
// Skapar den nya SVG-bilden
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Sparar SVG-bilden som en metafil
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Detta exempel visar hur man lägger till SVG-bilden som en metafil i presentationens bildsamling. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Skapar den nya SVG-bilden
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Sparar SVG-bilden som en metafil
svgImage->WriteAsEmf(memStream);
// Lägger till metafil i bildsamlingen
pres->get_Images()->AddImage(memStream->ToArray());
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../../system.io/stream/)
* Klass [ISvgImage](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: WriteAsEmf()
second_title: Aspose.Slides för C++ API-referens
description: Sparar SVG-bilden som en EMF-fil.
type: docs
weight: 66
url: /sv/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metod

Sparar SVG-bilden som en EMF-fil.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../../system.io/stream/)
* Klass [SvgImage](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
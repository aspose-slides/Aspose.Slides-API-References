---
title: WriteAsSvg()
second_title: Aspose.Slides voor C++ API-referentie
description: Slaat de slide-inhoud op als een SVG-bestand.
type: docs
weight: 157
url: /nl/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) methode

Slaat de slide-inhoud op als een SVG-bestand.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Doelstream |
## Opmerkingen

Het volgende codevoorbeeld laat zien hoe de eerste slide van een PowerPoint-presentatie wordt geconverteerd naar een SVG-bestand. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Slaat de eerste slide op als een SVG-bestand
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) methode

Slaat de slide-inhoud op als een SVG-bestand.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Doelstream |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-generatieopties |
## Opmerkingen

Het volgende codevoorbeeld laat zien hoe de eerste slide van een PowerPoint-presentatie wordt geconverteerd naar een SVG-bestand met opties. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Slaat de eerste slide op als een SVG-bestand
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [Slide](../)
* Klasse [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
---
title: WriteAsSvg()
second_title: Aspose.Slides för C++ API-referens
description: Sparar slide-innehållet som en SVG-fil.
type: docs
weight: 157
url: /sv/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) metod

Sparar slide-innehållet som en SVG-fil.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Måldataström |

## Anmärkningar

Följande kodexempel visar hur du konverterar den första sliden från en PowerPoint-presentation till en SVG-fil. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Sparar den första sliden som en SVG-fil
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) metod

Sparar slide-innehållet som en SVG-fil.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Måldataström |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-genereringsalternativ |

## Anmärkningar

Följande kodexempel visar hur du konverterar den första sliden från en PowerPoint-presentation till en SVG-fil med alternativ. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Sparar den första sliden som en SVG-fil
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../../system.io/stream/)
* Klass [Slide](../)
* Klass [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
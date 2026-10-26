---
title: WriteAsSvg()
second_title: Aspose.Slides für C++ API-Referenz
description: Speichert den Folieninhalt als SVG-Datei.
type: docs
weight: 157
url: /de/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) Methode

Speichert den Folieninhalt als SVG-Datei.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ziel-Stream |
## Hinweise

Das folgende Codebeispiel zeigt, wie die erste Folie einer PowerPoint-Präsentation in eine SVG-Datei konvertiert wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Speichert die erste Folie als SVG-Datei
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) Methode

Speichert den Folieninhalt als SVG-Datei.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ziel-Stream |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG-Erstellungsoptionen |
## Hinweise

Das folgende Codebeispiel zeigt, wie die erste Folie einer PowerPoint-Präsentation mit Optionen in eine SVG-Datei konvertiert wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Speichert die erste Folie als SVG-Datei
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [Slide](../)
* Klasse [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)
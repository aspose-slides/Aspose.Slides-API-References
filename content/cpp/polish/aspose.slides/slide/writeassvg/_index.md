---
title: WriteAsSvg()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zapisuje zawartość slajdu jako plik SVG.
type: docs
weight: 157
url: /pl/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) metoda

Zapisuje zawartość slajdu jako plik SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień docelowy |
## Uwagi

Poniższy przykład kodu demonstruje, jak przekonwertować pierwszy slajd z prezentacji PowerPoint na plik SVG. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Zapisuje pierwszy slajd jako plik SVG
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) metoda

Zapisuje zawartość slajdu jako plik SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień docelowy |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Opcje generowania SVG |
## Uwagi

Poniższy przykład kodu demonstruje, jak przekonwertować pierwszy slajd z prezentacji PowerPoint na plik SVG z opcjami. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Zapisuje pierwszy slajd jako plik SVG
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [Slide](../)
* Klasa [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
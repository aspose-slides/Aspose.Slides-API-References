---
title: WriteAsSvg()
second_title: Aspose.Slides pro C++ - reference API
description: Uloží obsah snímku jako soubor SVG.
type: docs
weight: 157
url: /cs/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) metoda


Uloží obsah snímku jako soubor SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Cílový proud |
## Poznámky



Následující ukázkový kód demonstruje, jak převést první snímek z prezentace PowerPoint do souboru SVG. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Uloží první snímek jako soubor SVG
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) metoda


Uloží obsah snímku jako soubor SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Cílový proud |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Možnosti generování SVG |
## Poznámky



Následující ukázkový kód demonstruje, jak převést první snímek z prezentace PowerPoint do souboru SVG s možnostmi. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Uloží první snímek jako soubor SVG
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [Slide](../)
* Třída [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
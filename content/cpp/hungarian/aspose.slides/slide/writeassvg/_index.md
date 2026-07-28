---
title: WriteAsSvg()
second_title: Aspose.Slides C++ API hivatkozás
description: A dia tartalmát SVG fájlként menti.
type: docs
weight: 157
url: /hu/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) metódus


A dia tartalmát SVG fájlként menti.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Cél adatfolyam |
## Megjegyzések



A következő kódrészlet bemutatja, hogyan lehet az első diát egy PowerPoint-prezentációból SVG-fájllá konvertálni. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Az első diát SVG fájlként menti
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) metódus


A dia tartalmát SVG fájlként menti.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Cél adatfolyam |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG generálási beállítások |
## Megjegyzések



A következő kódrészlet bemutatja, hogyan lehet az első diát egy PowerPoint-prezentációból SVG-fájllá konvertálni beállításokkal. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Az első diát SVG fájlként menti
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Slide](../)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
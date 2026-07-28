---
title: WriteAsEmf()
second_title: Aspose.Slides C++ API hivatkozás
description: Elmenti az SVG képet EMF fájlként.
type: docs
weight: 53
url: /hu/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metódus


Elmenti az SVG képet EMF fájlként.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Cél adatfolyam |
## Megjegyzések



A következő példa bemutatja, hogyan lehet az SVG képet metafájlba menteni. 
```cpp
// Létrehozza az új SVG képet
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Elmenti az SVG képet metafájlként
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Ez a példa bemutatja, hogyan lehet az SVG képet metafájlként hozzáadni a prezentáció képgyűjteményéhez. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Létrehozza az új SVG képet
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Elmenti az SVG képet metafájlként
svgImage->WriteAsEmf(memStream);
// Hozzáadja a metafájlt a képgyűjteményhez
pres->get_Images()->AddImage(memStream->ToArray());
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [ISvgImage](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
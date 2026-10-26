---
title: WriteAsEmf()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zapisuje obraz SVG jako plik EMF.
type: docs
weight: 53
url: /pl/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metoda

Zapisuje obraz SVG jako plik EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień docelowy |
## Uwagi



Poniższy przykład pokazuje, jak zapisać obraz SVG do metafilu. 
```cpp
// Tworzy nowy obraz SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Zapisuje obraz SVG jako metafile
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Ten przykład pokazuje, jak dodać obraz SVG jako metafil do kolekcji obrazów prezentacji. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tworzy nowy obraz SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Zapisuje obraz SVG jako metafile
svgImage->WriteAsEmf(memStream);
// Dodaje metafile do kolekcji obrazów
pres->get_Images()->AddImage(memStream->ToArray());
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [ISvgImage](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
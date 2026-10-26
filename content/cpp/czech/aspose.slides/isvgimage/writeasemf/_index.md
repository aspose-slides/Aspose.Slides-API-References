---
title: WriteAsEmf()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Uloží obrázek SVG jako soubor EMF.
type: docs
weight: 53
url: /cs/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metoda


Uloží obrázek SVG jako soubor EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Cílový proud |
## Poznámky



Následující příklad ukazuje, jak uložit obrázek SVG do metafile. 
```cpp
// Vytvoří nový SVG obrázek
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Uloží obrázek SVG jako metafájl
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Tento příklad ukazuje, jak přidat obrázek SVG jako metafile do kolekce obrázků prezentace. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Vytvoří nový SVG obrázek
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Uloží obrázek SVG jako metafájl
svgImage->WriteAsEmf(memStream);
// Přidá metafájl do kolekce obrázků
pres->get_Images()->AddImage(memStream->ToArray());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [ISvgImage](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
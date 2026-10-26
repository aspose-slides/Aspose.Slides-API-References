---
title: WriteAsEmf()
second_title: Aspose.Slides pro C++ - reference API
description: Uloží SVG obrázek jako soubor EMF.
type: docs
weight: 66
url: /cs/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metoda


Uloží SVG obrázek jako soubor EMF.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Cílový proud |
## Poznámky



Následující příklad ukazuje, jak uložit SVG obrázek do metafilu. 
```cpp
// Vytvoří nový SVG obrázek
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Uloží SVG obrázek jako metafil
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Tento příklad ukazuje, jak přidat SVG obrázek jako metafil do kolekce obrázků prezentace. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Vytvoří nový SVG obrázek
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Uloží SVG obrázek jako metafil
svgImage->WriteAsEmf(memStream);
// Přidá metafil do kolekce obrázků
pres->get_Images()->AddImage(memStream->ToArray());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [SvgImage](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
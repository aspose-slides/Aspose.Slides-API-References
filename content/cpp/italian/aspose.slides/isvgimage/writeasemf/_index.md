---
title: WriteAsEmf()
second_title: Riferimento API di Aspose.Slides per C++
description: Salva l'immagine SVG come file EMF.
type: docs
weight: 53
url: /it/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metodo

Salva l'immagine SVG come file EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di destinazione |

## Osservazioni

Il seguente esempio dimostra come salvare l'immagine SVG in un metafile. 
```cpp
// Crea la nuova immagine SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Salva l'immagine SVG come metafile
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Questo esempio dimostra come aggiungere l'immagine SVG come metafile alla raccolta di immagini della presentazione. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Crea la nuova immagine SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Salva l'immagine SVG come metafile
svgImage->WriteAsEmf(memStream);
// Aggiunge il metafile alla raccolta di immagini
pres->get_Images()->AddImage(memStream->ToArray());
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [ISvgImage](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
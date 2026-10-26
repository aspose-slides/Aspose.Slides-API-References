---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides für C++ API-Referenz
description: Komprimiert das Presentation, indem nicht verwendete Zeichen aus eingebetteten Schriftarten entfernt werden.
type: docs
weight: 27
url: /de/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) Methode

Komprimiert das [Presentation](../../../aspose.slides/presentation/), indem nicht verwendete Zeichen aus eingebetteten Schriften entfernt werden.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Präsentationsinstanz |

## Hinweise

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [Compress](../)
* Namensraum [Aspose::Slides::LowCode](../../)
* Bibliothek [Aspose.Slides](../../../)
---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wykonuje kompresję prezentacji poprzez usunięcie nieużywanych znaków z osadzonych czcionek.
type: docs
weight: 27
url: /pl/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) metoda

Wykonuje kompresję [Presentation](../../../aspose.slides/presentation/) przez usunięcie nieużywanych znaków z osadzonych czcionek.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Instancja prezentacji |

## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [Compress](../)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)
---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides pro C++ - reference API
description: Provádí kompresi prezentace odstraněním nepoužívaných znaků z vložených fontů.
type: docs
weight: 27
url: /cs/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) metoda

Provádí kompresi [Presentation](../../../aspose.slides/presentation/) odstraněním nepoužívaných znaků z vložených fontů.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Instance prezentace |
## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Presentation](../../../aspose.slides/presentation/)
* Třída [Compress](../)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Knihovna [Aspose.Slides](../../../)
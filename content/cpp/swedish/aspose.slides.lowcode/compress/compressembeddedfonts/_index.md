---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides för C++ API-referens
description: Komprimerar presentationen genom att ta bort oanvända tecken från inbäddade typsnitt.
type: docs
weight: 27
url: /sv/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) metod


Komprimerar [Presentation](../../../aspose.slides/presentation/) genom att ta bort oanvända tecken från inbäddade typsnitt.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentationinstansen |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [Compress](../)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: Compress
second_title: Aspose.Slides för C++ API-referens
description: Representerar en grupp metoder avsedda att komprimera Presentation.
type: docs
weight: 14
url: /sv/aspose.slides.lowcode/compress/
---
## Compress klass

Representerar en grupp metoder avsedda att komprimera [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Utför komprimering av [Presentation](../../aspose.slides/presentation/) genom att ta bort oanvända tecken från inbäddade teckensnitt. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Utför komprimering av [Presentation](../../aspose.slides/presentation/) genom att ta bort oanvända layoutbilder. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Utför komprimering av [Presentation](../../aspose.slides/presentation/) genom att ta bort oanvända masterbilder. |
## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Se också

* Namnrymd [Aspose::Slides::LowCode](../)
* Bibliotek [Aspose.Slides](../../)
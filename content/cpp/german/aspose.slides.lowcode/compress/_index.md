---
title: Compress
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Gruppe von Methoden dar, die zum Komprimieren von Presentation bestimmt sind.
type: docs
weight: 14
url: /de/aspose.slides.lowcode/compress/
---
## Compress Klasse


Stellt eine Gruppe von Methoden dar, die zum Komprimieren von [Presentation](../../aspose.slides/presentation/) bestimmt sind.

```cpp
class Compress
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Komprimiert das [Presentation](../../aspose.slides/presentation/), indem nicht verwendete Zeichen aus eingebetteten Schriftarten entfernt werden. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Komprimiert das [Presentation](../../aspose.slides/presentation/), indem nicht verwendete Layout-Folien entfernt werden. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Komprimiert das [Presentation](../../aspose.slides/presentation/), indem nicht verwendete Master-Folien entfernt werden. |
## Hinweise



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Namensraum [Aspose::Slides::LowCode](../)
* Bibliothek [Aspose.Slides](../../)
---
title: Compress
second_title: Aspose.Slides pro C++ API Reference
description: Představuje skupinu metod určených ke kompresi prezentace.
type: docs
weight: 14
url: /cs/aspose.slides.lowcode/compress/
---
## Compress třída

Představuje skupinu metod určených ke kompresi [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Provádí kompresi [Presentation](../../aspose.slides/presentation/) odstraněním nepoužívaných znaků z vložených písem. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Provádí kompresi [Presentation](../../aspose.slides/presentation/) odstraněním nepoužívaných snímků rozvržení. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Provádí kompresi [Presentation](../../aspose.slides/presentation/) odstraněním nepoužívaných hlavních snímků. |
## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Jmenný prostor [Aspose::Slides::LowCode](../)
* Knihovna [Aspose.Slides](../../)
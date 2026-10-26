---
title: Compress
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje grupę metod przeznaczonych do kompresji prezentacji.
type: docs
weight: 14
url: /pl/aspose.slides.lowcode/compress/
---
## Compress klasa


Reprezentuje grupę metod przeznaczonych do kompresji [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Wykonuje kompresję [Presentation](../../aspose.slides/presentation/) poprzez usunięcie nieużywanych znaków z osadzonych czcionek. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Wykonuje kompresję [Presentation](../../aspose.slides/presentation/) poprzez usunięcie nieużywanych slajdów układu. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Wykonuje kompresję [Presentation](../../aspose.slides/presentation/) poprzez usunięcie nieużywanych slajdów wzorca. |
## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zobacz również

* Przestrzeń nazw [Aspose::Slides::LowCode](../)
* Biblioteka [Aspose.Slides](../../)
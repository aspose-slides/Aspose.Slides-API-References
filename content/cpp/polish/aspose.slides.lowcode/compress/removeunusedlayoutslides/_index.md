---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Wykonuje kompresję Presentation poprzez usunięcie nieużywanych slajdów układu.
type: docs
weight: 14
url: /pl/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) metoda


Wykonuje kompresję [Presentation](../../../aspose.slides/presentation/) poprzez usunięcie nieużywanych slajdów układu.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Instancja prezentacji |
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [Compress](../)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)
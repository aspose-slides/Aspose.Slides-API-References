---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides för C++ API-referens
description: Komprimerar Presentation genom att ta bort oanvända layoutbilder.
type: docs
weight: 14
url: /sv/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) metod

Komprimerar [Presentation](../../../aspose.slides/presentation/) genom att ta bort oanvända layoutbilder.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentationinstansen |
## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [Compress](../)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)
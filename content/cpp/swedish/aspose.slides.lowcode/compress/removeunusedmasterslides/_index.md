---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides för C++ API-referens
description: Komprimerar Presentation genom att ta bort oanvända masterbilder.
type: docs
weight: 1
url: /sv/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) metod


Gör komprimering av [Presentation](../../../aspose.slides/presentation/) genom att ta bort oanvända masterbilder.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentationens instans |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [Compress](../)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Provádí kompresi prezentace odstraněním nepoužívaných hlavních snímků.
type: docs
weight: 1
url: /cs/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) metoda

Provádí kompresi [Presentation](../../../aspose.slides/presentation/) odstraněním nepoužívaných hlavních snímků.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Instance prezentace |
## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Presentation](../../../aspose.slides/presentation/)
* Třída [Compress](../)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
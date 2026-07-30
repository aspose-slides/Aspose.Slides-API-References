---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides pro C++ – reference API
description: Provádí kompresi prezentace odstraněním nepoužívaných snímků rozvržení.
type: docs
weight: 14
url: /cs/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) metoda

Provádí kompresi [Presentation](../../../aspose.slides/presentation/) odstraněním nepoužívaných snímků rozvržení.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Instance prezentace |

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Presentation](../../../aspose.slides/presentation/)
* Třída [Compress](../)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Knihovna [Aspose.Slides](../../../)
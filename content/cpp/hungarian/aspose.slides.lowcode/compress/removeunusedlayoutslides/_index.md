---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides for C++ API Referencia
description: A prezentáció tömörítését végzi a nem használt elrendezési diák eltávolításával.
type: docs
weight: 14
url: /hu/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) metódus

A [Presentation](../../../aspose.slides/presentation/) tömörítését végzi a nem használt elrendezési diák eltávolításával.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A prezentáció példánya |

## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [Compress](../)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)
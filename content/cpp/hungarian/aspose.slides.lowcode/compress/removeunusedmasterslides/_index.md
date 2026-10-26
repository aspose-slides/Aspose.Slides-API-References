---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides for C++ API Referencia
description: A Presentation tömörítését végzi a nem használt mesterdiák eltávolításával.
type: docs
weight: 1
url: /hu/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) metódus


A [Presentation](../../../aspose.slides/presentation/) tömörítését hajtja végre a nem használt mesterdiák eltávolításával.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A prezentáció példánya |
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [Compress](../)
* Névterület [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)
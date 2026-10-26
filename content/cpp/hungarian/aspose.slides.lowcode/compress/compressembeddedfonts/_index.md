---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides C++ API referencia
description: A prezentáció tömörítését végzi a beágyazott betűtípusok nem használt karaktereinek eltávolításával.
type: docs
weight: 27
url: /hu/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) metódus


Elvégzi a [Presentation](../../../aspose.slides/presentation/) tömörítését a beágyazott betűtípusokból a nem használt karakterek eltávolításával.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A prezentáció példány |
## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [Compress](../)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)
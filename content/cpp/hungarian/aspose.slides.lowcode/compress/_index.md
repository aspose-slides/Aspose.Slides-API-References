---
title: Compress
second_title: Aspose.Slides C++ API hivatkozás
description: A Presentation tömörítésére szolgáló metóduscsoportot képvisel.
type: docs
weight: 14
url: /hu/aspose.slides.lowcode/compress/
---
## Compress osztály


A [Presentation](../../aspose.slides/presentation/) tömörítésére szolgáló metóduscsoportot képvisel.

```cpp
class Compress
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | A [Presentation](../../aspose.slides/presentation/) tömörítését végzi a beágyazott betűkészletek nem használt karaktereinek eltávolításával. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | A [Presentation](../../aspose.slides/presentation/) tömörítését végzi a nem használt elrendezési diák eltávolításával. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | A [Presentation](../../aspose.slides/presentation/) tömörítését végzi a nem használt mesterdiák eltávolításával. |
## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Névtere [Aspose::Slides::LowCode](../)
* Könyvtár [Aspose.Slides](../../)
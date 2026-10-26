---
title: Compress
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un gruppo di metodi destinati a comprimere Presentation.
type: docs
weight: 14
url: /it/aspose.slides.lowcode/compress/
---
## Compress classe

Rappresenta un gruppo di metodi destinati a comprimere [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Effettua la compressione del [Presentation](../../aspose.slides/presentation/) rimuovendo i caratteri inutilizzati dai font incorporati. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Effettua la compressione del [Presentation](../../aspose.slides/presentation/) rimuovendo le diapositive di layout inutilizzate. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Effettua la compressione del [Presentation](../../aspose.slides/presentation/) rimuovendo le diapositive master inutilizzate. |

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Spazio dei nomi [Aspose::Slides::LowCode](../)
* Libreria [Aspose.Slides](../../)
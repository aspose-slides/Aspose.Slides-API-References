---
title: Compress
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un groupe de méthodes destiné à compresser une présentation.
type: docs
weight: 14
url: /fr/aspose.slides.lowcode/compress/
---
## Compress classe


Représente un groupe de méthodes destiné à compresser [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Effectue la compression du [Presentation](../../aspose.slides/presentation/) en supprimant les caractères inutilisés des polices intégrées. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Effectue la compression du [Presentation](../../aspose.slides/presentation/) en supprimant les diapositives de mise en page inutilisées. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Effectue la compression du [Presentation](../../aspose.slides/presentation/) en supprimant les diapositives maîtres inutilisées. |
## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Espace de noms [Aspose::Slides::LowCode](../)
* Bibliothèque [Aspose.Slides](../../)
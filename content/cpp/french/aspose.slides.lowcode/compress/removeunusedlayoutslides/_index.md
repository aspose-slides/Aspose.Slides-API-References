---
title: RemoveUnusedLayoutSlides()
second_title: Référence API Aspose.Slides pour C++
description: Effectue la compression de la Présentation en supprimant les diapositives de mise en page inutilisées.
type: docs
weight: 14
url: /fr/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) méthode

Effectue la compression du [Presentation](../../../aspose.slides/presentation/) en supprimant les diapositives de mise en page inutilisées.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | L'instance de présentation |
## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [Compress](../)
* Espace de noms [Aspose::Slides::LowCode](../../)
* Bibliothèque [Aspose.Slides](../../../)
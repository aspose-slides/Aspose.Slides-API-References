---
title: RemoveUnusedMasterSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue la compression de la présentation en supprimant les diapositives maîtres inutilisées.
type: docs
weight: 1
url: /fr/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) méthode


Effectue la compression du [Presentation](../../../aspose.slides/presentation/) en supprimant les diapositives maîtres inutilisées.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | L'instance de présentation |
## Remarques




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [Compress](../)
* Espace de noms [Aspose::Slides::LowCode](../../)
* Bibliothèque [Aspose.Slides](../../../)
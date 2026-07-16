---
title: get_PresentationLockingBehavior()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors du travail avec des BLOBs, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l'instance de Presentation. Voici un exemple :"
type: docs
weight: 1
url: /fr/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() méthode

Cette propriété définit si une instance de la classe [Presentation](../../presentation/) peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors du travail avec des BLOBs, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l'instance de [Presentation](../../presentation/). Voici un exemple :

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Remarques

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException sera levée car pres.pptx est verrouillé pendant la durée de vie d'une Presentation
    // File::Delete(u"pres.pptx");
}
// après la destruction de l'objet Presentation, le fichier est déverrouillé et peut être supprimé
IO::File::Delete(u"pres.pptx");
```

## Voir aussi

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Classe [IBlobManagementOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
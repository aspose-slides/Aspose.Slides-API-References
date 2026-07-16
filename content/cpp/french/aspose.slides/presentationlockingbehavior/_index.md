---
title: PresentationLockingBehavior
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente le comportement concernant le traitement de la source IPresentation (fichier ou System::IO::Stream) lors du chargement et de l'utilisation d'une instance d'IPresentation."
type: docs
weight: 6748
url: /fr/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior énumération


Représente le comportement concernant le traitement de la source [IPresentation](../ipresentation/) (fichier ou [System::IO::Stream](../../system.io/stream/)) lors du chargement et de l'utilisation d'une instance de [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| LoadAndRelease | 0 | La source sera verrouillée uniquement pendant la durée d'exécution du constructeur [IPresentation](../ipresentation/). |
| KeepLocked | 1 | La source sera verrouillée pendant toute la durée de vie de l'instance [IPresentation](../ipresentation/), jusqu'à ce qu'elle soit libérée. |

## Remarques


La source est le paramètre passé au constructeur [IPresentation](../ipresentation/). Dans l'exemple ci-dessous, la source est le fichier "pres.pptx" : 


```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```


Dans cet exemple, la source (fichier "pres.pptx") sera verrouillée pendant la durée de vie de l'instance [IPresentation](../ipresentation/), c’est-à-dire qu’elle ne peut pas être modifiée ou supprimée par un autre processus. 
## Voir aussi

* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)
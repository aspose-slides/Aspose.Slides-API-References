---
title: Equals()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si les deux instances IBaseSlide sont égales. La valeur de retour est calculée en fonction de la structure du diaporama et du contenu statique. Deux diaporamas sont égaux si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne tient pas compte des valeurs d'identifiants uniques, par exemple SlideId, et du contenu dynamique, par exemple la valeur de la date actuelle dans Date Placeholder.
type: docs
weight: 183
url: /fr/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) méthode

Détermine si les deux instances [IBaseSlide](../) sont égales. La valeur de retour est calculée en fonction de la structure du diaporama et du contenu statique. Deux diaporamas sont égaux si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne tient pas compte des valeurs d'identifiants uniques, par exemple SlideId, et du contenu dynamique, par exemple la valeur de la date actuelle dans Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | Le [IBaseSlide](../) à comparer avec le [IBaseSlide](../) actuel. |

### Valeur de retour

**true** si le [IBaseSlide](../) spécifié est égal au [IBaseSlide](../) actuel ; sinon, **false**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBaseSlide](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
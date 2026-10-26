---
title: Equals()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si les deux instances IBaseSlide sont égales. La valeur retournée est calculée à partir de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiants uniques, par ex. SlideId, et le contenu dynamique, par ex. la valeur de date actuelle dans Date Placeholder.
type: docs
weight: 170
url: /fr/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) méthode

Détermine si les deux instances [IBaseSlide](../../ibaseslide/) sont égales. La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiant uniques, par exemple SlideId, et le contenu dynamique, par exemple la valeur de date actuelle dans Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | Le [IBaseSlide](../../ibaseslide/) à comparer avec le [IBaseSlide](../../ibaseslide/) actuel. |

### Valeur de retour

**true** si le [IBaseSlide](../../ibaseslide/) spécifié est égal au [IBaseSlide](../../ibaseslide/) actuel ; sinon, **false**.

## Remarques

L'exemple suivant montre comment comparer deux diapositives. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBaseSlide](../../ibaseslide/)
* Classe [BaseSlide](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: GetEffective()
second_title: Référence API Aspose.Slides pour C++
description: Obtient les données de fond effectives avec l'héritage appliqué.
type: docs
weight: 118
url: /fr/aspose.slides/background/geteffective/
---
## Background::GetEffective() méthode


Obtient les données de fond effectives avec l'héritage appliqué.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Valeur de retour

Un [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Remarques



Cet exemple montre comment obtenir les propriétés de fond effectives. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Classe [Background](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
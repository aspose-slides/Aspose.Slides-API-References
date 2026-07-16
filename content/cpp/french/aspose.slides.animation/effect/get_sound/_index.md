---
title: get_Sound()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit le son intégré pour l'effet. Lire IAudio.
type: docs
weight: 170
url: /fr/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() méthode


Définit le son intégré pour l'effet. Lire [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Obtient la séquence d'effets pour la diapositive
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extrait le son de l'effet sous forme de tableau d'octets
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudio](../../../aspose.slides/iaudio/)
* Classe [Effect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)
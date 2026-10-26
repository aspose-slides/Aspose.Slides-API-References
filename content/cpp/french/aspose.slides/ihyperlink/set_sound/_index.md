---
title: set_Sound()
second_title: Référence API Aspose.Slides pour C++
description: Représente le son de lecture du lien hypertexte. Écrivez IAudio.
type: docs
weight: 196
url: /fr/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) méthode


Représente le son de lecture du lien hypertexte. Écrivez [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenir le premier hyperlien de forme
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extraire le son du hyperlien dans un tableau d'octets
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudio](../../iaudio/)
* Classe [IHyperlink](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
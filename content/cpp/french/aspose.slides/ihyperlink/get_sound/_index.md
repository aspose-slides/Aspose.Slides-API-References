---
title: get_Sound()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le son lu du lien hypertexte. Lire IAudio.
type: docs
weight: 183
url: /fr/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() méthode


Représente le son lu du lien hypertexte. Lire [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenir le premier lien hypertexte de la forme
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extraire le son du lien hypertexte sous forme de tableau d'octets
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IAudio](../../iaudio/)
* classe [IHyperlink](../)
* espace de noms [Aspose::Slides](../../)
* bibliothèque [Aspose.Slides](../../../)
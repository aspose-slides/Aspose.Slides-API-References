---
title: get_Sound()
second_title: Référence API Aspose.Slides pour C++
description: Représente le son lu du lien hypertexte. Lire IAudio.
type: docs
weight: 287
url: /fr/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() méthode


Représente le son lu du lien hypertexte. Lire [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Récupère le premier hyperlien de forme
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extrait le son du lien hypertexte sous forme de tableau d'octets
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IAudio](../../iaudio/)
* classe [Hyperlink](../)
* espace de noms [Aspose::Slides](../../)
* bibliothèque [Aspose.Slides](../../../)
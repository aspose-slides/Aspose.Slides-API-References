---
title: set_Sound()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le son de lecture du lien hypertexte. Écrivez IAudio.
type: docs
weight: 300
url: /fr/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) méthode

Représente le son de lecture du lien hypertexte. Écrivez [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
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
* Classe [IAudio](../../iaudio/)
* Classe [Hyperlink](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
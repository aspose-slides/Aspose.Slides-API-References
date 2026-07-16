---
title: SetMacroHyperlinkClick()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit le lien hypertexte macro lors d'un clic.
type: docs
weight: 79
url: /fr/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) méthode


Définir le lien hypertexte macro lors d'un clic.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nom de la macro |

### Return Value

[Hyperlink](../../hyperlink/) objet [IHyperlink](../../ihyperlink/)
## Remarques



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHyperlink](../../ihyperlink/)
* Classe [String](../../../system/string/)
* Classe [HyperlinkManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
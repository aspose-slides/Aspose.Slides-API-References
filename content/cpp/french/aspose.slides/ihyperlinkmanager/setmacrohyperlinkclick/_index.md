---
title: SetMacroHyperlinkClick()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un hyperlien macro lors d'un clic.
type: docs
weight: 79
url: /fr/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) méthode

Définit un hyperlien macro lors d'un clic.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nom de la macro |

### Valeur de retour

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)

## Remarques

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IHyperlink](../../ihyperlink/)
* classe [String](../../../system/string/)
* classe [IHyperlinkManager](../)
* espace de noms [Aspose::Slides](../../)
* bibliothèque [Aspose.Slides](../../../)
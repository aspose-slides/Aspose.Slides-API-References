---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides voor C++ API-referentie
description: Stel macro-hyperlink in bij een klik.
type: docs
weight: 79
url: /nl/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) methode

Stel macro-hyperlink in bij een klik.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Naam van de macro |

### Retourwaarde

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Opmerkingen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## Zie Ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHyperlink](../../ihyperlink/)
* Klasse [String](../../../system/string/)
* Klasse [IHyperlinkManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
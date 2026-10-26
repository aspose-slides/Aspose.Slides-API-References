---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides für C++ API-Referenz
description: Makro-Hyperlink bei einem Klick setzen.
type: docs
weight: 79
url: /de/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) Methode

Makro-Hyperlink bei einem Klick setzen.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Name des Makros |

### Rückgabewert

[Hyperlink](../../hyperlink/) Objekt [IHyperlink](../../ihyperlink/)
## Anmerkungen



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IHyperlink](../../ihyperlink/)
* Klasse [String](../../../system/string/)
* Klasse [HyperlinkManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)
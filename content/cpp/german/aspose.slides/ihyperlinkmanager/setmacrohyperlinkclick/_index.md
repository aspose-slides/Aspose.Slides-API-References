---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides für C++ API-Referenz
description: Makro-Hyperlink beim Klicken festlegen.
type: docs
weight: 79
url: /de/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) Methode

Makro-Hyperlink beim Klicken festlegen.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Name des Makros |

## Rückgabewert

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Hinweise



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHyperlink](../../ihyperlink/)
* Klasse [String](../../../system/string/)
* Klasse [IHyperlinkManager](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví makrohyperlink při kliknutí.
type: docs
weight: 79
url: /cs/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) metoda

Nastaví makrohyperlink při kliknutí.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Název makra |

### Návratová hodnota

[Hyperlink](../../hyperlink/) objekt [IHyperlink](../../ihyperlink/)
## Poznámky

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IHyperlink](../../ihyperlink/)
* třída [String](../../../system/string/)
* třída [IHyperlinkManager](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
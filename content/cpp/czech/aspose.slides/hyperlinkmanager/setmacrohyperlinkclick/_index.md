---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Nastaví hyperodkaz na makro při kliknutí.
type: docs
weight: 79
url: /cs/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) metoda


Nastavit hyperodkaz na makro při kliknutí.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Název makra |

### Návratová hodnota

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IHyperlink](../../ihyperlink/)
* Třída [String](../../../system/string/)
* Třída [HyperlinkManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
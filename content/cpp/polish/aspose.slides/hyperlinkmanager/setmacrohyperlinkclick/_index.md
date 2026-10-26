---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustaw hiperłącze makra po kliknięciu.
type: docs
weight: 79
url: /pl/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) metoda


Ustaw hiperłącze makra po kliknięciu.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nazwa makra |

### Wartość zwracana

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Uwagi



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IHyperlink](../../ihyperlink/)
* Klasa [String](../../../system/string/)
* Klasa [HyperlinkManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
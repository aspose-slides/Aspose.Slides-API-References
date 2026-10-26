---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustaw hiperłącze makra po kliknięciu.
type: docs
weight: 79
url: /pl/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) metoda


Ustaw hiperłącze makra po kliknięciu.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IHyperlink](../../ihyperlink/)
* Klasa [String](../../../system/string/)
* Klasa [IHyperlinkManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides för C++ API-referens
description: Ställ in makrohyperlänk på ett klick.
type: docs
weight: 79
url: /sv/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) metod

Ställ in makrohyperlänk på ett klick.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Namnet på makrot |

### Returvärde

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IHyperlink](../../ihyperlink/)
* Klass [String](../../../system/string/)
* Klass [IHyperlinkManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
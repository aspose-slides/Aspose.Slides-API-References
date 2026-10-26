---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides för C++ API-referens
description: Ställ in makrohyperlänk vid ett klick.
type: docs
weight: 79
url: /sv/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) metod


Ställ in makrohyperlänk vid ett klick.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Namn på makrot |

### Returvärde

[Hyperlink](../../hyperlink/) objekt [IHyperlink](../../ihyperlink/)
## Anmärkningar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IHyperlink](../../ihyperlink/)
* Klass [String](../../../system/string/)
* Klass [HyperlinkManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
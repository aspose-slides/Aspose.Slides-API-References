---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides C++ API referencia
description: Makróhivatkozás beállítása kattintáskor.
type: docs
weight: 79
url: /hu/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) metódus

Makróhivatkozás beállítása kattintáskor.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | A makró neve |

### Visszatérési érték

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Megjegyzések

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHyperlink](../../ihyperlink/)
* Class [String](../../../system/string/)
* Class [HyperlinkManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
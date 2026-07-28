---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides C++ API referencia
description: Makró hiperhivatkozás beállítása kattintáskor.
type: docs
weight: 79
url: /hu/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) method

Makró hiperhivatkozás beállítása kattintáskor.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | A makró neve |

### Visszatérési érték

[Hyperlink](../../hyperlink/) objektum [IHyperlink](../../ihyperlink/)
## Megjegyzések

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IHyperlink](../../ihyperlink/)
* Osztály [String](../../../system/string/)
* Osztály [IHyperlinkManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
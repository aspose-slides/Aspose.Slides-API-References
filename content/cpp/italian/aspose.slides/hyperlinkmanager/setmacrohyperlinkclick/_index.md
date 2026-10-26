---
title: SetMacroHyperlinkClick()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta collegamento ipertestuale macro al clic.
type: docs
weight: 79
url: /it/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) metodo


Imposta collegamento ipertestuale macro al clic.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nome della macro |

### Valore restituito

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Osservazioni



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHyperlink](../../ihyperlink/)
* Classe [String](../../../system/string/)
* Classe [HyperlinkManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
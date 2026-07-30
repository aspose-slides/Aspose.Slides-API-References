---
title: SetMacroHyperlinkClick()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta collegamento ipertestuale macro al clic.
type: docs
weight: 79
url: /it/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) metodo


Imposta collegamento ipertestuale macro al clic.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nome della macro |

### Valore di ritorno

[Hyperlink](../../hyperlink/) oggetto [IHyperlink](../../ihyperlink/)
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
* Classe [IHyperlinkManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
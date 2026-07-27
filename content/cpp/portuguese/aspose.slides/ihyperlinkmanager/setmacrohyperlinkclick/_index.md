---
title: SetMacroHyperlinkClick()
second_title: Referência da API Aspose.Slides para C++
description: Define hiperlink de Macro ao clicar.
type: docs
weight: 79
url: /pt/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) método

Define hiperlink de Macro ao clicar.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nome da macro |

### Valor de retorno

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Observações

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHyperlink](../../ihyperlink/)
* Classe [String](../../../system/string/)
* Classe [IHyperlinkManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
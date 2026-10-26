---
title: SetMacroHyperlinkClick()
second_title: Referência da API Aspose.Slides para C++
description: Define o hiperlink de macro ao clicar.
type: docs
weight: 79
url: /pt/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) método


Define o hiperlink de macro ao clicar.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nome da macro |

### Valor de Retorno

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHyperlink](../../ihyperlink/)
* Classe [String](../../../system/string/)
* Classe [HyperlinkManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
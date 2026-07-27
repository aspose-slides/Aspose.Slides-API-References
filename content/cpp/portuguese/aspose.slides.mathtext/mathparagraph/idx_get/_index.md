---
title: idx_get()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o item no índice especificado. Somente leitura IMathBlock.
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) método


Obtém o item no índice especificado. Somente leitura [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero do item a ser obtido |

### Valor de Retorno

O bloco de um texto matemático.
## Observações



Exemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)
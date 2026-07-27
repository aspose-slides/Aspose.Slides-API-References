---
title: idx_set()
second_title: Aspose.Slides para C++ Referência de API
description: Obtém o item no índice especificado. Somente leitura IMathBlock.
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathparagraph/idx_set/
---
## MathParagraph::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) method


Obtém o item no índice especificado. Somente leitura [IMathBlock](../../imathblock/).

```cpp
void Aspose::Slides::MathText::MathParagraph::idx_set(int32_t index, System::SharedPtr<IMathBlock> value) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero do item a obter |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | O bloco de um texto matemático. |
## Observações



Exemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)
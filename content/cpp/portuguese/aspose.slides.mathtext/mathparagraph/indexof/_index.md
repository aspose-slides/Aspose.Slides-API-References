---
title: IndexOf()
second_title: Referência da API Aspose.Slides para C++
description: Determina o índice de um IMathBlock específico na coleção.
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) método

Determina o índice de um [IMathBlock](../../imathblock/) específico na coleção.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | O item a localizar na coleção. |

### Valor de Retorno

O índice de *mathBlock* se encontrado na coleção; caso contrário, -1.

## Observações



Exemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
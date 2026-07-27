---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona IMathBlock ao final da coleção.
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) método


Adiciona [IMathBlock](../../imathblock/) ao final da coleção.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Um bloco matemático que será adicionado ao final da coleção |
## Observações



Exemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathParagraph](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
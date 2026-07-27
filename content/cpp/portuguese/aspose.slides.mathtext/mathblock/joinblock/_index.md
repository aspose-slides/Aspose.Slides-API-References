---
title: JoinBlock()
second_title: Referência da API Aspose.Slides para C++
description: Junta outro bloco matemático a este
type: docs
weight: 196
url: /pt/aspose.slides.mathtext/mathblock/joinblock/
---
## MathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) método


Junta outro bloco matemático a este

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::JoinBlock(System::SharedPtr<IMathBlock> other) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | O bloco de junção |

### Valor de Retorno

este bloco matemático após a junção
## Observações



Exemplo: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"c"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"a"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)
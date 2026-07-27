---
title: JoinBlock()
second_title: Referência da API Aspose.Slides para C++
description: Une outro bloco matemático a este
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathblock/joinblock/
---
## IMathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) método


Une outro bloco matemático a este

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlock::JoinBlock(System::SharedPtr<IMathBlock> other)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../)\> | O bloco que será unido |

### Valor de Retorno

este bloco matemático após a união
## Observações



Exemplo: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"c"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"a"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)
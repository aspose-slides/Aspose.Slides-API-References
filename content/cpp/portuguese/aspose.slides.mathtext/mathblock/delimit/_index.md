---
title: Delimit()
second_title: Aspose.Slides para C++ Referência da API
description: Delimita elementos filhos com caractere separador (sem os colchetes)
type: docs
weight: 209
url: /pt/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) método


Delimita elementos filhos com caractere separador (sem os colchetes)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separatorCharacter | char16_t | Caractere separador |

### Valor de Retorno

O elemento matemático do tipo [IMathDelimiter](../../imathdelimiter/)
## Observações



Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathDelimiter](../../imathdelimiter/)
* classe [MathBlock](../)
* namespace [Aspose::Slides::MathText](../../)
* biblioteca [Aspose.Slides](../../../)
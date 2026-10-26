---
title: Delimit()
second_title: Referência da API Aspose.Slides for C++
description: Delimita todos os elementos filhos com o caractere separador (sem os colchetes)
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) método

Delimita todos os elementos filhos com o caractere separador (sem os colchetes)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separatorCharacter | char16_t | Caractere usado como separador |

### Valor de Retorno

Instância do elemento [IMathDelimiter](../../imathdelimiter/)
## Observações

Exemplo:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)
---
title: CreateMathBar()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma barra matemática aplicando ao elemento
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) método

Cria uma barra matemática aplicando ao elemento

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático para aplicar a barra |

### Valor de Retorno

novo elemento de barra matemática

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) método

Cria uma barra matemática aplicando ao elemento

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático para aplicar a barra |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posição da barra |

### Valor de Retorno

novo elemento de barra matemática

## Veja Também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBar](../../imathbar/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBarFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
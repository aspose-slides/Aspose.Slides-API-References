---
title: CreateMathBar()
second_title: Aspose.Slides per C++ Riferimento API
description: Crea una barra matematica applicandola all'elemento
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) metodo

Crea una barra matematica applicandola all'elemento

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare la barra |

### Valore di ritorno

nuovo elemento barra matematica

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) metodo

Crea una barra matematica applicandola all'elemento

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare la barra |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posizione della barra |

### Valore di ritorno

nuovo elemento barra matematica

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBar](../../imathbar/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBarFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
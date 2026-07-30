---
title: CreateMathBar()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una barra matematica applicandola all'elemento
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) method

Crea una barra matematica applicandola all'elemento

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare la barra |

### Valore restituito

nuovo elemento barra matematica

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) method

Crea una barra matematica applicandola all'elemento

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare la barra |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posizione della barra |

### Valore restituito

nuovo elemento barra matematica

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBar](../../imathbar/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBarFactory](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)
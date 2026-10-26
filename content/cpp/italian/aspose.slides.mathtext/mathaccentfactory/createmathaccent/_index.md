---
title: CreateMathAccent()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un accento matematico applicato a un elemento matematico specificato con il valore predefinito del carattere di accento
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metodo

Crea un accento matematico applicato a un elemento matematico specificato con il valore predefinito del carattere di accento

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare l'accento |

### Valore di ritorno

nuovo accento matematico

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metodo

Crea un accento matematico applicato a un elemento matematico specificato

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare l'accento |
| accentCharacter | char16_t | carattere di accento |

### Valore di ritorno

nuovo accento matematico

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathAccentFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
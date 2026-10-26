---
title: CreateMathAccent()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un accento matematico applicato a un elemento matematico specificato con il valore predefinito del carattere di accento
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metodo

Crea un accento matematico applicato a un elemento matematico specificato con il valore predefinito del carattere di accento

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare l'accento |

### Valore restituito

nuovo accento matematico

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metodo

Crea un accento matematico applicato a un elemento matematico specificato

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matematico a cui applicare l'accento |
| accentCharacter | char16_t | carattere di accento |

### Valore restituito

nuovo accento matematico

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathAccentFactory](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)
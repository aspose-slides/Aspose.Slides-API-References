---
title: CreateMathAccent()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un acento matemático que se aplica a un elemento matemático especificado con el valor predeterminado del carácter de acento
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) método

Crea un acento matemático que se aplica a un elemento matemático especificado con el valor predeterminado del carácter de acento

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que se aplica el acento |

### Valor devuelto

nuevo acento matemático

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) método

Crea un acento matemático que se aplica a un elemento matemático especificado

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que se aplica el acento |
| accentCharacter | char16_t | carácter de acento |

### Valor devuelto

nuevo acento matemático

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathAccent](../../imathaccent/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathAccentFactory](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)
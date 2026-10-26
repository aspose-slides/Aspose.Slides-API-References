---
title: Enclose()
second_title: Aspose.Slides para C++ Referência da API
description: Envolve um elemento matemático entre parênteses
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() método

Envolve um elemento matemático entre parênteses

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### Valor de retorno

O elemento matemático do tipo [IMathDelimiter](../../imathdelimiter/) que inclui os parênteses

## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) método

Envolve este elemento em caracteres especificados, como parênteses ou outros caracteres como moldura

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char16_t | Caractere final (geralmente colchete direito) |

### Valor de retorno

O elemento matemático do tipo [IMathDelimiter](../../imathdelimiter/) que inclui os caracteres especificados como moldura

## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
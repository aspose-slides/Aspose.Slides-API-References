---
title: Enclose()
second_title: Referência da API Aspose.Slides para C++
description: Envolve um elemento matemático em parênteses
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() método


Envolve um elemento matemático em parênteses

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Valor de Retorno

O elemento matemático do tipo [IMathDelimiter](../../imathdelimiter/) que inclui os parênteses
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) método


Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char16_t | Caractere final (geralmente colchete direito) |

### Valor de Retorno

O elemento matemático do tipo [IMathDelimiter](../../imathdelimiter/) que inclui os caracteres especificados como moldura
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
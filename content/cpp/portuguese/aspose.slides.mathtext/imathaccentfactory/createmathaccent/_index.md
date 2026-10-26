---
title: CreateMathAccent()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um acento matemático aplicando a um elemento matemático especificado com o valor padrão do caractere de acento
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) método

Cria um acento matemático aplicando a um elemento matemático especificado com o valor padrão do caractere de acento

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar o acento |

### Valor de Retorno

novo acento matemático

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) método

Cria um acento matemático aplicando a um elemento matemático especificado

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar o acento |
| accentCharacter | char16_t | caractere de acento |

### Valor de Retorno

novo acento matemático

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathAccentFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
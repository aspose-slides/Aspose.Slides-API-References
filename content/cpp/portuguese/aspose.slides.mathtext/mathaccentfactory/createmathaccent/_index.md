---
title: CreateMathAccent()
second_title: Referência da API Aspose.Slides para C++
description: Cria um acento matemático aplicando a um elemento matemático especificado com o valor padrão do caractere de acento
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) método


Cria um acento matemático aplicando a um elemento matemático especificado com o valor padrão do caractere de acento

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar o acento |

### Valor de retorno

novo acento matemático

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) método


Cria um acento matemático aplicando a um elemento matemático especificado

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar o acento |
| accentCharacter | char16_t | caractere de acento |

### Valor de retorno

novo acento matemático

## Veja Também

* Definição de tipo [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathAccentFactory](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)
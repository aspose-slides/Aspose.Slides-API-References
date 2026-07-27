---
title: CreateMathematicalText()
second_title: Aspose.Slides para C++ Referência da API
description: Criar elemento de texto matemático vazio
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() método

Cria um elemento de texto matemático vazio

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### Valor de Retorno

novo Texto Matemático

## MathematicalTextFactory::CreateMathematicalText(char16_t) método

Cria um elemento de texto matemático com o valor especificado

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathSymbol | char16_t | símbolo único a ser usado como valor de texto |

### Valor de Retorno

novo Texto Matemático

## MathematicalTextFactory::CreateMathematicalText(System::String) método

Cria um elemento de texto matemático vazio com o valor especificado

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |

### Valor de Retorno

novo Texto Matemático

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) método

Cria um elemento de texto matemático vazio com o valor especificado e propriedades de formatação

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | configurações de formato de texto |

### Valor de Retorno

novo Texto Matemático

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathematicalText](../../imathematicaltext/)
* Classe [MathematicalTextFactory](../)
* Classe [String](../../../system/string/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
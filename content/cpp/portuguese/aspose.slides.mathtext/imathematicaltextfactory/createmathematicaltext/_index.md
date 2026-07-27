---
title: CreateMathematicalText()
second_title: Referência da API Aspose.Slides para C++
description: Criar elemento de texto matemático vazio
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() método

Criar elemento de texto matemático vazio

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Valor de Retorno

novo Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) método

Criar elemento de texto matemático com o valor especificado

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathSymbol | char16_t | símbolo único a ser usado como valor de texto |

### Valor de Retorno

novo Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) método

Criar elemento de texto matemático vazio com o valor especificado

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |

### Valor de Retorno

novo Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) método

Criar elemento de texto matemático vazio com o valor especificado e propriedades de formatação

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | configurações de formato de texto |

### Valor de Retorno

novo Mathematical Text

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathematicalText](../../imathematicaltext/)
* Classe [IMathematicalTextFactory](../)
* Classe [String](../../../system/string/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
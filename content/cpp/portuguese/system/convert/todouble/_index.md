---
title: ToDouble()
second_title: Referência da API Aspose.Slides para C++
description: Converte o valor booleano especificado para um número de ponto flutuante de dupla precisão equivalente.
type: docs
weight: 222
url: /pt/system/convert/todouble/
---
## Convert::ToDouble(bool) método

Converte o valor booleano especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) método

Converte o inteiro sem sinal de 8 bits especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) método

Converte o inteiro com sinal de 8 bits especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) método

Converte o inteiro sem sinal de 16 bits especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) método

Converte o inteiro com sinal de 16 bits especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) método

Converte o inteiro sem sinal de 32 bits especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) método

Converte o inteiro com sinal de 32 bits especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) método

Converte o inteiro sem sinal de 64 bits especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) método

Converte o inteiro com sinal de 64 bits especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) método

Converte o número de precisão simples especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) método

Retorna o número double especificado.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) método

Converte o número decimal especificado para um número de ponto flutuante de dupla precisão equivalente.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) método

Converte a string nula especificada para o valor de ponto flutuante de dupla precisão equivalente.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```

### Valor de retorno

Zero.

## Convert::ToDouble(const char_t *) método

Converte a c-string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser convertida |

### Valor de retorno

O valor de ponto flutuante de dupla precisão igual ao número representado pela c-string especificada

## Convert::ToDouble(const String\&) método

Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente.

```cpp
static double System::Convert::ToDouble(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |

### Valor de retorno

O valor de ponto flutuante de dupla precisão igual ao número representado pela string especificada

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação fornecidas.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string |

### Valor de retorno

O valor de ponto flutuante de dupla precisão igual ao número representado pela string especificada

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) método




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação e o estilo numérico fornecidos.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enum NumberStyles que especifica o estilo permitido da representação da string de um número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string |

### Valor de retorno

O valor de ponto flutuante de dupla precisão igual ao número representado pela string especificada

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Converte o valor boxed especificado para um valor de ponto flutuante de dupla precisão. Se o tipo do valor boxed for [String](../../string/), o formato de string especificado é usado durante a conversão.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O ponteiro compartilhado para o objeto que contém o valor boxed a ser convertido |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O formato de string a ser usado se o tipo do valor boxed for [String](../../string/) |

### Valor de retorno

Um valor de ponto flutuante de dupla precisão equivalente ao valor boxed especificado

## Veja também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
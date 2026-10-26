---
title: ToSingle()
second_title: Referência da API Aspose.Slides para C++
description: Converte o valor booleano especificado em um número de ponto flutuante de precisão simples equivalente.
type: docs
weight: 209
url: /pt/system/convert/tosingle/
---
## Convert::ToSingle(bool) método

Converte o valor booleano especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```
## Convert::ToSingle(uint8_t) método

Converte o inteiro sem sinal de 8 bits especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```
## Convert::ToSingle(int8_t) método

Converte o inteiro com sinal de 8 bits especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```
## Convert::ToSingle(uint16_t) método

Converte o inteiro sem sinal de 16 bits especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```
## Convert::ToSingle(int16_t) método

Converte o inteiro com sinal de 16 bits especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```
## Convert::ToSingle(uint32_t) método

Converte o inteiro sem sinal de 32 bits especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```
## Convert::ToSingle(int32_t) método

Converte o inteiro com sinal de 32 bits especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```
## Convert::ToSingle(uint64_t) método

Converte o inteiro sem sinal de 64 bits especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```
## Convert::ToSingle(int64_t) método

Converte o inteiro com sinal de 64 bits especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```
## Convert::ToSingle(float) método

Retorna o número float especificado.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```
## Convert::ToSingle(double) método

Converte o número de precisão dupla especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```
## Convert::ToSingle(const Decimal\&) método

Converte o número decimal especificado em um número de ponto flutuante de precisão simples equivalente.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```
## Convert::ToSingle(char_t) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```
## Convert::ToSingle(DateTime) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```
## Convert::ToSingle(std::nullptr_t) método

Converte a string nula especificada no valor de ponto flutuante de precisão simples equivalente.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Valor de Retorno

Zero.

## Convert::ToSingle(const char_t *) método

Converte a c-string contendo a representação textual de um número no valor de ponto flutuante de precisão simples equivalente.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser convertida |

### Valor de Retorno

O valor de ponto flutuante de precisão simples equivalente ao número representado pela c-string especificada

## Convert::ToSingle(const String\&) método

Converte a string contendo a representação textual de um número no valor de ponto flutuante de precisão simples equivalente.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |

### Valor de Retorno

O valor de ponto flutuante de precisão simples equivalente ao número representado pela string especificada

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Converte a string contendo a representação textual de um número no valor de ponto flutuante de precisão simples equivalente usando as informações de formatação fornecidas.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string |

### Valor de Retorno

O valor de ponto flutuante de precisão simples equivalente ao número representado pela string especificada

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) método

```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Converte a string contendo a representação textual de um número no valor de ponto flutuante de precisão simples equivalente usando as informações de formatação e o estilo numérico fornecidos.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bitwise dos valores do enum NumberStyles que especifica o estilo permitido da representação textual de um número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string |

### Valor de Retorno

O valor de ponto flutuante de precisão simples equivalente ao número representado pela string especificada

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) método

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Converte o valor encapsulado especificado em um valor de ponto flutuante de precisão simples.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O ponteiro compartilhado para o objeto que encapsula o valor a ser convertido |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O formato de string a ser usado se o tipo do valor encapsulado for [String](../../string/) |

### Valor de Retorno

Um valor de ponto flutuante de precisão simples equivalente ao valor encapsulado especificado

## Veja Também

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
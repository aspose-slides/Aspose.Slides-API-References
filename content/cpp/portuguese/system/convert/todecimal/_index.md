---
title: ToDecimal()
second_title: Referência da API Aspose.Slides para C++
description: Converte o valor booleano especificado para um número decimal equivalente.
type: docs
weight: 235
url: /pt/system/convert/todecimal/
---
## Convert::ToDecimal(bool) method

Converte o valor booleano especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) method

Converte o inteiro sem sinal de 8 bits especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) method

Converte o inteiro com sinal de 8 bits especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) method

Converte o inteiro sem sinal de 16 bits especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) method

Converte o inteiro com sinal de 16 bits especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) method

Converte o inteiro sem sinal de 32 bits especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) method

Converte o inteiro com sinal de 32 bits especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) method

Converte o inteiro sem sinal de 64 bits especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) method

Converte o inteiro com sinal de 64 bits especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) method

Converte o número float especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) method

Converte o número double especificado para um número decimal equivalente.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) method

Retorna o número decimal especificado.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) method

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) method

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) method

Converte a string nula especificada para o valor equivalente [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### Valor de Retorno

Zero.

## Convert::ToDecimal(const char_t *) method

Converte a c-string contendo a representação textual de um número para o valor equivalente [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser convertida |

### Valor de Retorno

O valor [Decimal](../../decimal/) igual ao número representado pela c-string especificada

## Convert::ToDecimal(const String\&) method

Converte a string contendo a representação textual de um número para o valor equivalente [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |

### Valor de Retorno

O valor [Decimal](../../decimal/) igual ao número representado pela string especificada

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Converte a string contendo a representação textual de um número para o valor equivalente [Decimal](../../decimal/) usando as informações de formatação fornecidas.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string |

### Valor de Retorno

O valor [Decimal](../../decimal/) igual ao número representado pela string especificada

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Converte a string contendo a representação textual de um número para o valor equivalente [Decimal](../../decimal/) usando os estilos de número e as informações de formatação especificados.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores do enum NumberStyles que especifica o estilo permitido da representação textual de um número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string |

### Valor de Retorno

O valor [Decimal](../../decimal/) igual ao número representado pela string especificada

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

Converte o valor encapsulado especificado para o valor equivalente [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O ponteiro compartilhado para o objeto que encapsula o valor a ser convertido |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O formato de string a ser usado se o tipo do valor encapsulado for [String](../../string/) |

### Valor de Retorno

Um valor [Decimal](../../decimal/) equivalente ao valor encapsulado especificado

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
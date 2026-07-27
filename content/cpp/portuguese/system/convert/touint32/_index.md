---
title: ToUInt32()
second_title: Referência da API Aspose.Slides para C++
description: Converte o valor booleano especificado para um inteiro sem sinal de 32 bits equivalente.
type: docs
weight: 170
url: /pt/system/convert/touint32/
---
## Convert::ToUInt32(bool) método

Converte o valor booleano especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) método

Converte o inteiro sem sinal de 8 bits especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) método

Converte o inteiro com sinal de 8 bits especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) método

Converte o inteiro sem sinal de 16 bits especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) método

Converte o inteiro com sinal de 16 bits especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) método

Retorna o inteiro sem sinal de 32 bits especificado.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) método

Converte o inteiro com sinal de 32 bits especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) método

Converte o inteiro sem sinal de 64 bits especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) método

Converte o inteiro com sinal de 64 bits especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) método

Converte o número em ponto flutuante especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) método

Converte o número double especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) método

Converte o número decimal especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) método

Converte o caractere unicode especificado para um inteiro sem sinal de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) método

A conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) método

Converte a string nula especificada para o valor inteiro sem sinal de 32 bits equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```

### Valor de Retorno

Zero.

## Convert::ToUInt32(const char_t *) método

Converte a c-string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser convertida |

### Valor de Retorno

O valor inteiro sem sinal de 32 bits igual ao número representado pela c-string especificada

## Convert::ToUInt32(const String\&) método

Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |

### Valor de Retorno

O valor inteiro sem sinal de 32 bits igual ao número representado pela string especificada

## Convert::ToUInt32(const String\&, int) método

Converte a string especificada contendo a representação textual de um número na base especificada para o valor inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| from_base | int | A base do número representado pela string |

### Valor de Retorno

O valor inteiro sem sinal de 32 bits igual ao número representado pela string especificada

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 32 bits equivalente usando as informações de formatação fornecidas.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string |

### Valor de Retorno

O valor inteiro sem sinal de 32 bits igual ao número representado pela string especificada

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 32 bits equivalente usando as informações de formatação fornecidas e o estilo numérico.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores do enum NumberStyles que especifica o estilo permitido da representação textual de um número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string |

### Valor de Retorno

O valor inteiro sem sinal de 32 bits igual ao número representado pela string especificada

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) método

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) método

```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Converte o valor encapsulado especificado para o valor inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O ponteiro compartilhado para o objeto que encapsula o valor a converter |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O formato de string a ser usado se o tipo do valor encapsulado for [String](../../string/) |

### Valor de Retorno

Um valor inteiro sem sinal de 32 bits equivalente ao valor encapsulado especificado

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
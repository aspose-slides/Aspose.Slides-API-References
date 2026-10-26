---
title: ToInt32()
second_title: Referência da API Aspose.Slides para C++
description: Converte o valor booleano especificado em um inteiro com sinal de 32 bits equivalente.
type: docs
weight: 157
url: /pt/system/convert/toint32/
---
## Convert::ToInt32(bool) método

Converte o valor booleano especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```
## Convert::ToInt32(uint8_t) método

Converte o inteiro sem sinal de 8 bits especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```
## Convert::ToInt32(int8_t) método

Converte o inteiro com sinal de 8 bits especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```
## Convert::ToInt32(uint16_t) método

Converte o inteiro sem sinal de 16 bits especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```
## Convert::ToInt32(int16_t) método

Converte o inteiro com sinal de 16 bits especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```
## Convert::ToInt32(uint32_t) método

Converte o inteiro sem sinal de 32 bits especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```
## Convert::ToInt32(int32_t) método

Retorna o inteiro com sinal de 32 bits especificado.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```
## Convert::ToInt32(uint64_t) método

Converte o inteiro sem sinal de 64 bits especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```
## Convert::ToInt32(int64_t) método

Converte o inteiro com sinal de 64 bits especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(int64_t value)
```
## Convert::ToInt32(float) método

Converte o número float especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(float value)
```
## Convert::ToInt32(double) método

Converte o número double especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(double value)
```
## Convert::ToInt32(const Decimal\&) método

Converte o número decimal especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```
## Convert::ToInt32(char_t) método

Converte o caractere unicode especificado em um inteiro com sinal de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```
## Convert::ToInt32(DateTime) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```
## Convert::ToInt32(std::nullptr_t) método

Converte a string nula especificada para o valor inteiro de 32 bits equivalente.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Valor de retorno

Zero.

## Convert::ToInt32(const char_t *) método

Converte a c-string contendo a representação textual de um número para o valor inteiro de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser convertida |

### Valor de retorno

O valor inteiro de 32 bits igual ao número representado pela c-string especificada

## Convert::ToInt32(const String\&) método

Converte a string contendo a representação textual de um número para o valor inteiro de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |

### Valor de retorno

O valor inteiro de 32 bits igual ao número representado pela string especificada

## Convert::ToInt32(const String\&, int) método

Converte a string contendo a representação textual de um número na base especificada para o valor inteiro de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| from_base | int | A base do número representado pela string |

### Valor de retorno

O valor inteiro de 32 bits igual ao número representado pela string especificada

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Converte a string contendo a representação textual de um número para o valor inteiro de 32 bits equivalente usando as informações de formatação fornecidas.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string |

### Valor de retorno

O valor inteiro de 32 bits igual ao número representado pela string especificada

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) método




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Converte a string contendo a representação textual de um número para o valor inteiro de 32 bits equivalente usando as informações de formatação e o estilo numérico fornecidos.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação textual do número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string |

### Valor de retorno

O valor inteiro de 32 bits igual ao número representado pela string especificada

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) método




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Converte o valor encapsulado especificado para um valor inteiro de 32 bits equivalente.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O ponteiro compartilhado para o objeto que encapsula o valor a ser convertido |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O formato de string a ser usado se o tipo do valor encapsulado for [String](../../string/) |

### Valor de retorno

Um valor inteiro de 32 bits equivalente ao valor encapsulado especificado

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
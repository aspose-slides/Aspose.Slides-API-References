---
title: ToInt64()
second_title: Referência da API Aspose.Slides para C++
description: Converte o valor booleano especificado para um inteiro assinado de 64 bits equivalente.
type: docs
weight: 183
url: /pt/system/convert/toint64/
---
## Convert::ToInt64(bool) método


Converte o valor booleano especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) método


Converte o inteiro sem sinal de 8 bits especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) método


Converte o inteiro assinado de 8 bits especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) método


Converte o inteiro sem sinal de 16 bits especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) método


Converte o inteiro assinado de 16 bits especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) método


Converte o inteiro sem sinal de 32 bits especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) método


Converte o inteiro assinado de 32 bits especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) método


Converte o inteiro sem sinal de 64 bits especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) método


Retorna o inteiro assinado de 64 bits especificado.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) método


Converte o número float especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) método


Converte o número double especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) método


Converte o número decimal especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) método


Converte o caractere unicode especificado para um inteiro assinado de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) método


Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) método


Converte a string nula especificada para o valor inteiro de 64 bits equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```


### Valor de Retorno

Zero.

## Convert::ToInt64(const char_t *) método


Converte a c-string especificada contendo a representação textual de um número para o valor inteiro de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser convertida |

### Valor de Retorno

O valor inteiro de 64 bits igual ao número representado pela c-string especificada

## Convert::ToInt64(const String\&) método


Converte a string especificada contendo a representação textual de um número para o valor inteiro de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |

### Valor de Retorno

O valor inteiro de 64 bits igual ao número representado pela string especificada

## Convert::ToInt64(const String\&, int) método


Converte a string especificada contendo a representação textual de um número na base especificada para o valor inteiro de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| from_base | int | A base do número representado pela string |

### Valor de Retorno

O valor inteiro de 64 bits igual ao número representado pela string especificada

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Converte a string especificada contendo a representação textual de um número para o valor inteiro de 64 bits equivalente usando as informações de formatação fornecidas.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string |

### Valor de Retorno

O valor inteiro de 64 bits igual ao número representado pela string especificada

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Converte a string especificada contendo a representação textual de um número para o valor inteiro de 64 bits equivalente usando as informações de formatação fornecidas e o estilo numérico.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores do enum NumberStyles que especifica o estilo permitido da representação textual de um número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string |

### Valor de Retorno

O valor inteiro de 64 bits igual ao número representado pela string especificada

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) método




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método


Converte o valor encapsulado especificado para um valor inteiro de 64 bits equivalente.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O ponteiro compartilhado para o objeto que encapsula o valor a ser convertido |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O formato da string a ser usado se o tipo do valor encapsulado for [String](../../string/) |

### Valor de Retorno

Um valor inteiro de 64 bits equivalente ao valor encapsulado especificado

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [Decimal](../../decimal/)
* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Classe [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)
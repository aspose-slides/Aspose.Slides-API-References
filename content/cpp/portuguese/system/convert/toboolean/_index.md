---
title: ToBoolean()
second_title: Referência de API do Aspose.Slides para C++
description: Retorna o valor booleano especificado.
type: docs
weight: 79
url: /pt/system/convert/toboolean/
---
## Convert::ToBoolean(bool) método

Retorna o valor booleano especificado.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) método

Converte o inteiro sem sinal de 8 bits especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) método

Converte o inteiro com sinal de 8 bits especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) método

Converte o inteiro sem sinal de 16 bits especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) método

Converte o inteiro com sinal de 16 bits especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) método

Converte o inteiro sem sinal de 32 bits especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) método

Converte o inteiro com sinal de 32 bits especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) método

Converte o inteiro sem sinal de 64 bits especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) método

Converte o inteiro com sinal de 64 bits especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) método

Converte o número float especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) método

Converte o número double especificado para um valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) método

Converte o número decimal especificado para um valor booleano equivalente.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) método

A conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) método

A conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) método

Converte a null-string especificada para o valor booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### Valor de Retorno

Falso.

## Convert::ToBoolean(const char_t *) método

Converte a c-string especificada para o valor do tipo bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser convertida |

### Valor de Retorno

True se a c-string especificada for igual a "True" e false se a c-string especificada for igual a "False".

## Convert::ToBoolean(const String\&) método

Converte a string especificada para o valor do tipo bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |

### Valor de Retorno

True se a c-string especificada for igual a "True" e false se a string especificada for igual a "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Converte a string especificada para o valor do tipo bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |

### Valor de Retorno

True se a c-string especificada for igual a "True" e false se a string especificada for igual a "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Converte o valor boxed especificado para um valor booleano equivalente.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O ponteiro compartilhado para o objeto que encapsula o valor a ser convertido |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O formato de string a ser usado se o tipo do valor boxed for [String](../../string/) |

### Valor de Retorno

Um valor booleano equivalente ao valor boxed especificado

## Ver Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Decimal](../../decimal/)
* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
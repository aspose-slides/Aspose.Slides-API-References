---
title: ToChar()
second_title: Referência da API Aspose.Slides para C++
description: A conversão não é suportada. Sempre lança InvalidCastException.
type: docs
weight: 118
url: /pt/system/convert/tochar/
---
## Convert::ToChar(bool) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) método

Converte o inteiro sem sinal de 8 bits especificado para um caractere unicode equivalente.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) método

Converte o inteiro com sinal de 8 bits especificado para um caractere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) método

Converte o inteiro sem sinal de 16 bits especificado para um caractere unicode equivalente.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) método

Converte o inteiro com sinal de 16 bits especificado para um caractere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) método

Converte o inteiro sem sinal de 32 bits especificado para um caractere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) método

Converte o inteiro com sinal de 32 bits especificado para um caractere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) método

Converte o inteiro sem sinal de 64 bits especificado para um caractere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) método

Converte o inteiro com sinal de 64 bits especificado para um caractere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) método

Retorna o caractere unicode especificado.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) método

Conversão não é suportada. Sempre lança InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) método

Converte o primeiro e único caractere da c-string especificada para um valor char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser convertida; espera-se que a c-string tenha exatamente 1 caractere. |

### Valor de Retorno

O primeiro e único caractere da c-string especificada se ela tiver exatamente 1 caractere, caso contrário - 0

## Convert::ToChar(const String\&) método

Converte o primeiro e único caractere da string especificada para um valor char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida; espera-se que a string tenha exatamente 1 caractere |

### Valor de Retorno

O primeiro e único caractere da string especificada se ela tiver exatamente 1 caractere, caso contrário - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Converte o primeiro e único caractere da string especificada para um valor char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida; espera-se que a string tenha exatamente 1 caractere |

### Valor de Retorno

O primeiro e único caractere da string especificada se ela tiver exatamente 1 caractere, caso contrário - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Converte o valor encapsulado especificado para um caractere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O ponteiro compartilhado para o objeto que encapsula o valor a ser convertido |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O formato de string a ser usado se o tipo do valor encapsulado for [String](../../string/) |

### Valor de Retorno

Um caractere unicode equivalente ao valor encapsulado especificado

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Decimal](../../decimal/)
* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [Object](../../object/)
* Estrutura [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)